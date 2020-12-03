---
title: Contattami
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: Per metterti in contatto compila il form sottostante.
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nome
        default_value: Il tuo nome
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Il tuo indirizzo email
        is_required: true
      - input_type: select
        name: Oggetto
        label: Oggetto
        default_value: Seleziona
        options:
          - Errore nel Sito
          - Collaborazione
          - Altro
        is_required: false
      - input_type: textarea
        name: message
        label: Messaggio
        default_value: Il tuo Messaggio
      - input_type: checkbox
        name: consent
        label: ' Sono consapevole che questo modulo sta memorizzando le mie informazioni in modo che io possa essere contattato.'
    submit_label: Send Message
layout: advanced
---
