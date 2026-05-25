# Privacy Policy

**Lychee Technology**
**Effective date:** April 24, 2026
**Last updated:** April 24, 2026

## 1. Who we are

Lychee Technology ("Lychee Technology", "we", "us") operates a real-time
order printing application for TikTok Shop sellers. We can be contacted
at: toml@crystal-expo.com.

## 2. Scope

This Privacy Policy describes how we collect, use, store, and protect
personal data in connection with our order printing service. It applies
to TikTok Shop sellers who authorize our application and to the order
data we receive through the TikTok Shop Partner API.

## 3. What data we collect

Through the TikTok Shop Partner API, we receive and process the
following categories of data when an order is placed in an authorized
shop:

- Order identifiers (order ID, order status, timestamps)
- Buyer identifiers (TikTok buyer user ID)
- Order line items (SKU, product name, quantity)
- Shipping address (only after the 1-hour TikTok Shop pending period)

We do not request or process payment card information, financial
account information, government-issued identifiers, or special
categories of personal data.

## 4. How we use this data

We process the above data for the sole purpose of generating printed
order receipts on the seller's local thermal printer, enabling the
seller to fulfill orders in real time during high-volume live selling
events. We do not use the data for advertising, profiling, analytics,
machine learning training, or resale.

## 5. Lawful basis for processing

Where the GDPR or analogous laws apply, our lawful basis for processing
is the legitimate interest of the seller in fulfilling orders placed
through their TikTok Shop, with the seller acting as the data
controller and Lychee Technology as the data processor.

## 6. How we store and protect data

- Order data is processed in memory and used immediately to print a
  receipt.
- A minimal record (order ID, status code, print timestamp) is
  retained in a local database for the sole purpose of preventing
  duplicate printing.
- Audit logs of webhook receipts are retained for 30 days, then
  automatically deleted.
- All data in transit is protected with TLS 1.2 or higher.
- Data at rest is protected by full-disk encryption on the systems
  where it resides.
- Access to systems and credentials follows the principle of least
  privilege.

## 7. Data sharing

We do not sell, rent, or otherwise share personal data with third
parties. The only outbound transmission of data from our application
is to the seller's own local thermal printer.

## 8. Subprocessors

We use the following service providers in the operation of our
service. Each is bound by appropriate confidentiality and data
protection commitments:

- **Cloudflare, Inc.** — provides the secure tunnel through which
  webhook traffic from TikTok Shop is delivered to our application.
  Cloudflare does not retain webhook payload contents.
- **GitHub, Inc.** — hosts our private source code repositories.

## 9. Data retention

- Deduplication identifiers: retained for 90 days
- Audit logs: retained for 30 days
- Cryptographic credentials: retained for the duration of the
  authorization, deleted upon revocation
- All data: deleted within 30 days of termination of the
  authorization or upon a documented deletion request

## 10. Your rights

Depending on your jurisdiction, you may have the right to:

- Request access to personal data we hold about you
- Request correction or deletion of personal data
- Object to or restrict certain processing
- Lodge a complaint with a data protection authority

To exercise these rights, contact us at toml@crystal-expo.com. We will
respond within 30 days, or sooner where required by applicable law.

## 11. International transfers

We do not transfer personal data outside the United States. All
processing occurs on infrastructure located in the United States,
operated by personnel located in the United States.

## 12. Children's data

Our service is not directed at children under the age of 13 (or
under 16 in jurisdictions where that is the applicable age), and
we do not knowingly process personal data from children.

## 13. Changes to this policy

We may update this Privacy Policy from time to time. The "Last
updated" date at the top of this policy reflects the most recent
revision. Material changes will be communicated to authorized
sellers via the contact information on file.

## 14. Contact

For any privacy questions or to exercise your rights, contact:
toml@crystal-expo.com