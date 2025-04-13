# GenZen Assessment Form

A multi-step assessment form component for Astro projects.

## Features

- Multi-step form with progress tracking
- Responsive design
- Alpine.js for interactivity
- Customizable styling

## Installation

```bash
npm install genzen-assessment-form
```

## Usage

```astro
---
import AssessmentForm from 'genzen-assessment-form/src/components/AssessmentForm.astro';
---

<AssessmentForm />
```

## Customization

The form can be customized by passing props:

```astro
<AssessmentForm 
  title="Custom Title"
  submitUrl="https://your-api-endpoint.com/submit"
/>
```

## License

MIT 