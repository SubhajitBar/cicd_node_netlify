#  CI/CD by using Github Actions and Railway
            
    deploy:
    name: Deploy
    needs: [test] #Our test must pass in order to run deploy job
    runs-on: ubuntu-latest
