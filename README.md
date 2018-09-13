# dPay Script

An Open JSON Standard for Trusted Workflows

### Account json_metadata

```json
{
    "profile": {
        "name": "Jared Rice Sr.",
        "about": "Creator of dWeb and dPay",
        "location": "Dallas",
        "website": "https://jrice.io",
        "cover_image": "https://img.dsocial.io/@jared/cover",
        "profile_image": "https://img.dsocial.io/@jared",
        "gender": "male",
        "email": "jared@dsite.io",
        "birthday": "12/31/1999",
        "timezone": "-5",
        "locale": "en_US",
        "languages": ["en"],
        "featured_post": "the-first-phase-of-the-steem-faq-and-wikee-consolidation-of-knowledge"
    },
    "dns": {"records":[["@","CNAME","dpay.io"]]}}
}
```

## Account Guidelines

### Profile

- `name`: max. length 20 chars.
- `about`: max. length 160 chars.
- `location`: max. length 30 chars.
- `website`: valid `https://` URL with max. length 100 chars.
- `profile_image`: image URL, preferably square-cropped with a minimum size of 230 x 230 pixels.

### Comment json_metadata

```json
{
  "app": "dsite/1.23",
  "format": "html",
  "tags": ["dsite", "dpay"],
  "users": ["jared", "stan"],
  "images": ["https://img.dsite.io/@jared"],
  "videos": [
    "https://www.youtube.com/watch?v=rkQ7b-u8_6g",
    "https://www.youtube.com/watch?v=H399YZ0pv0o"
  ],
  "status": "archived",
  "canonical":
    "http://blog.dsite.io/dsite/@jared/the-first-phase-of-the-dpay-faq-and-wikee-consolidation-of-knowledge"
}
```
