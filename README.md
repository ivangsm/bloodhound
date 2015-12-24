# bloodhound
An extensible packet sniffer application that can filter and monitor network traffic. It also has capabilities of producing alerts.

## Design

TBD

## Dependencies

- [gopacket](https://github.com/google/gopacket) for packet sniffing
- [ginkgo](https://github.com/onsi/ginkgo) for BDD style tests
- [gomega](github.com/onsi/gomega) for matchers used to create assertions in gingko

## Building 

Run the below command in the

```bash
godep go build
```

## Running tests

Run the below command in the directory of the top most directory of the project.

```bash
godep go test ./...
```

## Documentation

TBD

## License

bloodhound is released under the [MIT License](https://opensource.org/licenses/MIT).
