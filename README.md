erreq
=====

The erreq package defines an extension of the error interface which supports equality checking.

```go
type Error interface {
    error
    Equals(Error) bool
}
```
