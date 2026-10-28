# Dr Babu Kunadian — Website

Live: https://sandhya1975.github.io/drbabukunadian-site

## Files
| File | What it is |
|---|---|
| `index.html` | The website |
| `babu-portrait.jpg` | Hero photo |
| `babu-lhch.jpg` | About-section photo |
| `reviews.json` | Patient reviews shown on the site |

## How to add a patient review (Michele)
Patient reviews sent through the website arrive by email. To publish one:

1. Open `reviews.json` on GitHub and click the ✏️ pencil.
2. Add the review between the square brackets, like this:

```json
[
  {
    "name": "Sarah T.",
    "rating": 5,
    "text": "Dr Kunadian explained everything clearly and put me at ease.",
    "source": "Website",
    "date": "October 2026"
  }
]
```

3. For more than one review, separate each `{ ... }` with a comma.
4. Click **Commit changes**. The site updates in about a minute.

Rules:
- Only publish genuine reviews where the patient ticked "happy to be shown".
- Use first name or initials only. Remove any medical details.
- `rating` is a number from 1 to 5.

## Enquiry and review forms
Both forms email **michele.white@lhch.nhs.uk** using FormSubmit (free).
The **first** time a form is used, FormSubmit sends Michele an activation email. She must click **Activate** once, or no messages will be delivered.
