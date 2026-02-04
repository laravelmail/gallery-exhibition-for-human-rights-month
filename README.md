# Gallery Exhibition For Human Rights Month

Professional invitation email for a gallery exhibition during Human Rights Month

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Arts & Culture
- **Message Type:** Events
- **Tags:** human rights, exhibition

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/gallery-exhibition-for-human-rights-month.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/gallery-exhibition-for-human-rights-month/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.gallery-exhibition-for-human-rights-month',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
