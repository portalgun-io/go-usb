# go-usb
An in-progress port of libusb to Go

# Current state

OS-Agnostic code is converted and needs to be passed over for compile errors:

Syntax: 
* [x] backend.go
* [x] core.go
* [x] descriptor.go
* [x] hotplug.go
* [x] io.go
* [x] io_unix.go
* [x] io_windows.go
* [x] libusb.go
* [x] libusbi.go
* [x] list.go
* [x] strerror.go
* [x] sync.go

Semantic:
* [ ] backend.go
* [ ] core.go
* [ ] descriptor.go
* [ ] hotplug.go
* [ ] io.go
* [ ] io_unix.go
* [ ] io_windows.go
* [ ] libusb.go
* [ ] libusbi.go
* [ ] list.go
* [ ] strerror.go
* [ ] sync.go

OS-Specific code is in the process of conversion
