<div align="center">
  <a href="https://oblador.github.io/hush/"><img src="https://user-images.githubusercontent.com/378279/102943111-6dfe0500-44b7-11eb-9e9a-1c77d53a04ab.png" width="256" height="256"></a>
  <h1>Hush w/ Mojave (macOS 10.14) and Catalina (macOS 10.15) support</h1>
  <p>
    <b>Block nags to accept cookies and privacy invasive tracking in Safari</b>
  </p>
  <br>
  <br>
  <br>
</div>
Many thanks to karstenBriksoft for making support for Mojave and Catalina possible in the first place. See his fork 

[KarstenBriksoft/hush](https://github.com/karstenBriksoft/hush)
<br>
<br>
This fork is used only to update and merge all changes to the blocklist from the original repository.


## Building from source

To build the app in Xcode, you need to have [deno](https://deno.land) installed first:

```sh
brew install deno
xcode-select --install
```

## Contributing

### Tests

Run blocklist unit tests with:
```bash
make test_unit
```


### Blocklist

Compile blocklist only with (part of Xcode build):
```bash
make blocklist
```

## License

Hush: [MIT License](http://opensource.org/licenses/mit-license.html). © Joel Arvidsson 2020-present

[Fanboy List](https://easylist.to): [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). © Rick Petnel and contributors 2005
