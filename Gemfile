source 'https://rubygems.org'
gem 'jekyll', '4.2.1'
install_if -> { ENV["GITHUB_ACTIONS"] != "true" } do
    puts "Is GitHub action: #{ENV["GITHUB_ACTIONS"] == "true"}"
    gem "webrick", "~> 1.8"
end 