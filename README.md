# Separate provisionings

## Main

From root: 

```bash
azd provision
```

## Infra subfolder without azure.yml

From root: 

```bash
azd provision -C sub1-infra-sub/infra
```

## Infra subfolder with azure.yml

From root: 

```bash
azd provision -C sub2-infra-sub-azureyml
```

## Infra no sub

From root: 

```bash
azd provision -C sub3-nosub
```