---
icon: /media/hashnode.svg
label: Hashnode
tags:
    - guides
---

# Hashnode Blog

Wenn du einen Hashnode-Blog erstellst, gibt dir Hashnode eine kostenlose hashnode.dev domain. Allerdings kannst du deine is-a.dev einrichten.
In dieser Anleitung erfährst du, wie du dies erreichst.

---

1. Logge dich in dein Hashnode-Konto ein.

2. Klicke auf dein Avatar in der unteren-linken Bildschirmecke auf dem **Desktop** oder der oberen-rechten Ecke auf dem **Smartphone**.
   ![Hashnode's Feed](https://cdn.hashnode.com/res/hashnode/image/upload/v1614932849541/cBNDGKXMj.png?auto=compress)

3. Klicke auf **Blog Dashboard**
   ![Hashnode's Feed](https://cdn.hashnode.com/res/hashnode/image/upload/v1614937218081/InvxVHXDy.png?auto=compress)

4. Klicke auf den **Custom Domain-Tab** und gebe deine Domain ***ohne*** www oder https:// ein. Klicke dann auf **Update**
   ![Hashnode's Blog Domain Tab](https://cdn.hashnode.com/res/hashnode/image/upload/v1614937377176/0cwddAywO.png?auto=compress)

### Die Domain-Datei erstellen

In dem `domains` Ordner, erstelle eine neue JSON-Datei für deine Subdomain (`domains/subdomain.json`) und erstelle ein Pull-Request. Diese Datei sollte folgendes erhalten:

```json
{
    "owner": {
        "username": "dein-github-nutzername",
        "email": "deine-email@dein-email-provider.com"
    },
    "record": {
        "CNAME": "hashnode.network"
    }
}
```

## Konfiguration

Deine Seite sollte erreichbar sein, nachdem dein PR akzeptiert wurde. Das kann aber ca. 24 Stunden dauern.

## Benötigst du mehr Hilfe?

- [Hashnode Domain Mapping Guide](https://support.hashnode.com/docs/mapping-domain/)
- [Hashnode Support Center](https://support.hashnode.com/)



Hashnode ist in keinem Weg mit is-a.dev assoziert.
