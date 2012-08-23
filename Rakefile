desc "Generate website and deploy to production server"
task :deploy do
  puts `nanoc`
  puts `scp -r output/* drugcamp@78.46.129.32:/var/lib/drugcamp/public/`
end
