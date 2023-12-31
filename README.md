# Install Apprentice Licenses

This Github Action will install a Houdini Apprentice License.

```yaml
    - name: Install License
      uses: captainhammy/install-houdini-apprentice-license-action@v1
      with:
        client_id: ${{ secrets.SESI_CLIENT_ID }}
        client_secret_key:  ${{ secrets.SESI_SECRET_KEY }}
        houdini_version: 19.5  # Optional
```

This action uses the [SideFX Web API](https://www.sidefx.com/docs/api/) to redeem the necessary licenses. You must provide your [Client id and Client secret](https://www.sidefx.com/docs/api/credentials/index.html) values.
