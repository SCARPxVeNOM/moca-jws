# JWKS Endpoint

This repository contains a JSON Web Key Set (JWKS) endpoint for GitHub Pages.

## About

This repository hosts a JWKS (JSON Web Key Set) file that can be used for JWT token verification. The JWKS endpoint is accessible via GitHub Pages.

## Usage

The JWKS endpoint is available at:
```
https://[your-username].github.io/[repository-name]/jwks.json
```

## File Structure

- `jwks.json` - The JSON Web Key Set containing public keys for JWT verification

## Security Note

This repository contains public keys only. Private keys should never be committed to version control.

## GitHub Pages

This repository is configured to work with GitHub Pages, making the JWKS endpoint publicly accessible for JWT verification purposes.
