Hello Mistral Developers!

Here are some things that you can use when adding new APIs/services!

# Mistral.cs

## Mistral.LogRequest

`await mistral.LogRequest();` - This logs all data about the current request, headers, json, and form data.

## Mistral.Form

`mistral.Form` - This class contains data about the current request's form. Usually, you can use `[FromForm]` in the request's method parameters. But if the current request has multiple unknown parameters, you can use `mistral.Form`.

# Important Notes

We do NOT allow the use of AI in Mistral projects besides from deobfuscating response models for the backend.
