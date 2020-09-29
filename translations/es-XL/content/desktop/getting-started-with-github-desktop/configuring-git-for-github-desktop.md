---
title: Configurar Git para GitHub Desktop
shortTitle: Configuring Git
intro: 'Si todavía no tienes Git instalado, debes configurarlo antes de usar GitHub Desktop.'
versions:
  free-pro-team: '*'
---

{{ site.data.variables.product.prodname_desktop }} uses the email address you set in your local Git configuration to connect commits with your account on {{ site.data.variables.product.product_name}}.

{{ site.data.reusables.desktop.update-email-address }}

{% tip %}

**Tip**: Cualquiera podrá ver la dirección de correo electrónico en tu configuración de Git si haces confirmaciones públicas. Para obtener más información, consulta "[Establecer tu dirección de correo electrónico de confirmación](/articles/setting-your-commit-email-address)."

{% endtip %}

{% mac %}

{{ site.data.reusables.desktop.sign-in-choose-product }}
{{ site.data.reusables.user_settings.access_settings }}
{{ site.data.reusables.user_settings.emails }}
{{ site.data.reusables.desktop.copy-email-git-config }}
{{ site.data.reusables.desktop.return-to-desktop }}
{{ site.data.reusables.desktop.mac-select-desktop-menu }}
7. In the Preferences window, click **Git**. ![El panel de Git en el menú Preferences (Preferencias)](/assets/images/help/desktop/mac-select-git-pane.png)
{{ site.data.reusables.desktop.name-field-git-config }}
  ![El campo con el nombre de la configuración de Git](/assets/images/help/desktop/mac-name-git-config.png)
{{ site.data.reusables.desktop.paste-email-git-config }}
  ![La dirección de correo electrónico copiada en el campo de configuración de Git](/assets/images/help/desktop/mac-email-git-config.png)
{{ site.data.reusables.desktop.click-save-git-config }}
  ![Save button in Git configuration field](/assets/images/help/desktop/mac-save-git-config.png)

{% endmac %}

{% windows %}

{{ site.data.reusables.desktop.sign-in-choose-product }}
{{ site.data.reusables.user_settings.access_settings }}
{{ site.data.reusables.user_settings.emails }}
{{ site.data.reusables.desktop.copy-email-git-config }}
{{ site.data.reusables.desktop.return-to-desktop }}
{{ site.data.reusables.desktop.windows-choose-options }}
8. In the Options window, click **Git**. ![El panel de Git en el menú Options (Opciones)](/assets/images/help/desktop/windows-select-git-pane.png)
{{ site.data.reusables.desktop.name-field-git-config }}
  ![El campo con el nombre de la configuración de Git](/assets/images/help/desktop/windows-name-git-config.png)
{{ site.data.reusables.desktop.paste-email-git-config }}
  ![La dirección de correo electrónico copiada en el campo de configuración de Git](/assets/images/help/desktop/windows-email-git-config.png)
{{ site.data.reusables.desktop.click-save-git-config }}
  ![Save button in Git configuration field](/assets/images/help/desktop/windows-save-git-config.png)

{% endwindows %}

### Leer más

- [Agregar una dirección de correo electrónico a tu cuenta de GitHub](/articles/adding-an-email-address-to-your-github-account/)"
- "[Establecer tu dirección de correo electrónico de confirmación](/articles/setting-your-commit-email-address)."