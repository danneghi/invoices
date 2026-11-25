# Invoices

A mobile invoicing app for creating, previewing, and sending PDF invoices. Your data stays on this device (nothing is uploaded to a server).

**Live app:** https://danneghi.github.io/invoices/

## Add to your iPhone Home Screen

1. Open the live app in Safari (not Chrome or a saved tab inside another browser).
2. Tap the Share button, then **Add to Home Screen**.
3. Tap **Add**. The orange checkmark icon will appear on your Home Screen.

## Features

- Business profile, logo, GST, payment notes, and Alberta GST 5% by default
- Clients and reusable items
- Auto-numbered invoices and estimates, tax, discounts, and overdue status
- Invoice preview and PDF sharing via Mail, Messages, or WhatsApp
- JSON backup export and import in Settings

Data is stored in the browser under `invoices-app-v1`. There is no service worker; PDF libraries load from a CDN when you send or download an invoice.
