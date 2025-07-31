#### IMPORTANT #######################################################
# Gemfile is for local development ONLY; Gemfile is NOT loaded in CI #
####################################################### IMPORTANT ####
# On CI we only need the gemspecs' dependencies (including development dependencies).
# Exceptions, if any, such as for Appraisals, are in gemfiles/*.gemfile

source "https://rubygems.org"

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }
git_source(:gitlab) { |repo_name| "https://gitlab.com/#{repo_name}" }

gem "rake", "~> 13.0"

### Audit
eval_gemfile "gemfiles/modular/audit.gemfile"

### Documentation
eval_gemfile "gemfiles/modular/documentation.gemfile"

### Style
eval_gemfile "gemfiles/modular/style.gemfile"
