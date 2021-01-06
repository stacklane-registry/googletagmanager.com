# Google Tag Manager

A [Stacklane Connector](https://stacklane.com/docs/api/connectors) for [Google Tag Manager](https://marketingplatform.google.com/about/tag-manager/).

## Import

/🔌.yaml

```
- https://github.com/stacklane-registry/googletagmanager.com.git#!v1.0.0
```

## Tag Usage

Applies the correct Content-Security-Policy and includes the `<script>` tag.

```
<head>
...
<googletagmanager.com-setup async id="YOUR-TAG-MANAGER-ID"/>
...
</head>
```
