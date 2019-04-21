## Cert Tool

#### Usage

1. Generate root CA cert
```sh
# generate root CA cert
bash -c "$(curl -k https://raw.githubusercontent.com/QCute/CertTool/refs/heads/master/cert-tool)" -s ca

```

2. Generate [example.com]() cert
```sh
# generate root CA cert
bash -c "$(curl -k https://raw.githubusercontent.com/QCute/CertTool/refs/heads/master/cert-tool)" -s cert example.com
```

#### Help
    USAGE: bash [ca | cert example.com | clean]

    Available environment variable specific cert parameter
        COUNTRY                Cert Country Name
        STATE                  Cert State Name
        LOCATION               Cert Location Name
        ORGANIZATION           Cert Organization Name
        ORGANIZATION_UNIT      Cert Organization Unit Name
        COMMON_NAME            Cert Common Name
        EMAIL                  Cert Email