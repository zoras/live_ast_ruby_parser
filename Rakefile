require_relative 'devel/levitate'

Levitate.new "live_ast_ruby_parser" do |s|
  s.camel_name = "LiveASTRubyParser"
  s.developers << ["James M. Lawrence", "quixoticsycophant@gmail.com"]
  s.username = "quix"
  s.required_ruby_version = ">= 1.9.2"
  s.description = s.summary
  s.dependencies = [
    ["ruby_parser", "~> 3.2.2"],
    ["ruby2ruby", "~> 2.0.6"],
  ]
end

task :test do
  puts "Testing is done with the LiveAST test suite."
end

task :default => :test
