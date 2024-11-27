# Secret File GH Action

GH Action to create files from secrets

## Usage
```
- uses: NillionNetwork/secret-file-action@v0.1.0
  with:
    secret: ${{ secrets.APPLE_DEV_CERTIFICATE_PASSWORD_FILE }}
    file: "apple-auth/my_developerID_application.p12.password"
```

### Inputs

* secret: file content in base64, loaded from secrets  
* file: path to the file where the content will be written
