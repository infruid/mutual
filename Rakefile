desc "Run all the pirate tests"
task "test" do
  FileList["test/*.coffee"].exclude("test/helpers.coffee").each do |path|
    sh "coffee #{path}"
  end
end