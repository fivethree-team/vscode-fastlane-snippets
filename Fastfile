version = fiv_update_version(pathToConfigXML: "./config.xml")
fiv_bump_version(message: "bump version: #{version}"})
outputpath = fiv_ionic(
    platform: "browser"
    release: "true"
    prod: "true"
)
puts "output path of build: #{outputpath}"

desc "Cool description"
lane :lanename do |options|
    #add actions here
end

app_identifier "com.example.app" # The bundle identifier of your app
apple_id "user@example.com"  # Your Apple email address
# team_name "Team"
# team_id "Q2CBPJ58CA"
# To select a team for App Store Connect use
# itc_team_name "Company"
# itc_team_id "18742801"
