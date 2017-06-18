# problem statement
gets an azure storage account key

# example usage

> note: in examples, VERSION represents a version of the azure.storage.account.key.get pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.storage.account.key.get#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.storage.account.key.get#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/azure.storage.account.key.get#VERSION }
    inputs:
      subscriptionId:
      loginId:
      loginSecret:
      resourceGroup:
      storageAccount:
      # begin optional args
      key:
      loginTenantId:
      loginType:
      # end optional args
    outputs:
      key:
```
