# go-iex-test

## DESCRIPTION
Testing package for `github.com/jonwho/go-iex`.

## USE
Export ENV VAR

```sh
export IEX_TEST_SECRET_TOKEN=Tsk_ahsvyao12u4u0ausvn1o3rhw988120yf_FAKE
export IEX_TEST_PUBLISHABLE_TOKEN=Tpk_la091720ihakbso128uihotbfao_FAKE
export IEX_SECRET_TOKEN=Tsk_ahsvyao12u4u0ausvn1o3rhw988120yf_REAL
export IEX_PUBLISHABLE_TOKEN=Tpk_la091720ihakbso128uihotbfao_REAL
```

Test whole suite.
`go test`
Test specific function.
`go test -run Batch`

Real tokens will only be used to test data weights that are free and unavailable to testing tokens.