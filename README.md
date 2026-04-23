# Portbase Kiro Workshop

## Workshop Environment

https://catalog.us-east-1.prod.workshops.aws/join?access-code=026d-0b6350-42

### Fix for backend/scripts/prepare-lambda-packages.sh on linux

⏺ Fixed code for line 35-38:

          # Update the import path in the function file
          # This sed command replaces '../../common/middleware' with './middleware'
          # Using .bak extension for cross-platform compatibility (macOS and Linux)
          sed -i.bak "s|require('../../common/middleware')|require('./middleware')|g" $package_dir/$(basename $function_path)
          rm -f $package_dir/$(basename $function_path).bak

## Evaluation Link 

 https://www.metricsthatmatter.com/url/u.aspx?AC0CA832F234573565

## Survey link :
https://pulse.aws/survey/BJXJJHUY?p=0

## Support & Questions : 
Email : bbrice@amazon.nl

