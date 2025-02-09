---
title: Administrar la verificación de firma de confirmación de cambios
intro: '{% data variables.product.product_name %} will verify GPG{% ifversion ssh-commit-verification %}, SSH,{% endif %} or S/MIME signatures so other people will know that your commits come from a trusted source.{% ifversion fpt %} {% data variables.product.product_name %} will automatically sign commits you make using the {% data variables.product.product_name %} web interface.{% endif %}'
redirect_from:
  - /articles/generating-a-gpg-key
  - /articles/signing-commits-with-gpg
  - /articles/managing-commit-signature-verification
  - /github/authenticating-to-github/managing-commit-signature-verification
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Identity
  - Access management
children:
  - /about-commit-signature-verification
  - /displaying-verification-statuses-for-all-of-your-commits
  - /checking-for-existing-gpg-keys
  - /generating-a-new-gpg-key
  - /adding-a-gpg-key-to-your-github-account
  - /telling-git-about-your-signing-key
  - /associating-an-email-with-your-gpg-key
  - /signing-commits
  - /signing-tags
shortTitle: Verificar las firmas de confirmación
---

