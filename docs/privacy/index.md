# Privacy Policy

**Last updated:** October 19, 2026

This policy explains what information VargaLABS ("we") collects when you use SIGMA software and the SIGMA licence
service at `api.vargalabs.com`, why we collect it, and how long we keep it.

Who we are: VargaLABS, a business operated by Steven Varga, Toronto, Ontario, Canada.
Contact for privacy questions: [info@vargalabs.com](mailto:info@vargalabs.com).

## What we collect

### 1. Licence check-in

When SIGMA software checks its licence, it sends:

- the **installation key** that identifies your licence;
- a **machine fingerprint**: a one-way SHA-256 hash made on your computer. We cannot get your hardware details,
  computer name or user name back from it;
- the **product name and version**.

We record when each machine was first and last seen. We use this to issue licence tokens, to enforce the number
of machines your licence allows, and to offer software updates.

**Kept:** a machine record is deleted automatically 30 days after the machine was last seen. A record of a
licence rule being broken (for example, too many machines) is deleted after 365 days.

### 2. Linking an installation to an account (optional)

If you choose to link an installation, you sign in with GitHub, Google or LinkedIn. That provider tells us:

- your account ID at that provider;
- your email address, if the provider gives one (for GitHub, only your verified primary email);
- your display name.

We use this only to connect your installations to you, so that we can contact you about
your licence. We use the provider's access to your account once, during sign-in, and we do not keep it.
We never receive your password.

**Kept:** the short link session is deleted after 10 minutes. Your linked account record is kept while your
licence is active, and is deleted on request.

### 3. Error reports (optional)

If SIGMA software reports an error, it sends the installation key, the product name and version, and the text
of the error report. We remove links, mentions and hidden markup from the text, and file it as an issue in a
private GitHub repository that only VargaLABS staff can read.

**Kept:** the report record on our servers is deleted after 30 days. The issue in the private repository is kept
until the problem is fixed and the issue is closed or removed.

### 4. Payments

When you buy a licence, Stripe processes the payment. Stripe collects your card details and billing address under
its own privacy policy. We receive the name, email address, country and amount of the purchase, and the last four
digits of the card. We never receive the full card number.

**Kept:** payment records are kept as long as Canadian tax law requires, currently at least six years.

### 5. Server logs

Our servers log the IP address, request path, status and response time of each request, to protect the service
against abuse and to fix problems. **Kept:** 30 days.

## What we do not do

- We do not use cookies, advertising or tracking on the licence service.
- We do not sell or rent your information.
- We do not read your files, data or source code. The licence service receives only what is listed above.

## Who processes your information

| Service | What for | Where |
|---|---|---|
| Amazon Web Services | runs the licence service and stores the records above | United States (us-east-1) |
| GitHub | private repository for error reports; sign-in if you choose GitHub | United States |
| Google | sign-in, if you choose Google | United States |
| LinkedIn | sign-in, if you choose LinkedIn | United States |
| Stripe | payments, if you buy a licence | Canada and the United States |

Your information may therefore be stored and processed outside your own country, including in the United States.

## Security

Data is encrypted in transit (HTTPS) and at rest. Signing keys and provider secrets are encrypted with AWS KMS.
Access to the records is limited to VargaLABS administrators.

## Your rights

You can ask us to show, correct or delete the information we hold about you, or unlink an account, by writing to
[info@vargalabs.com](mailto:info@vargalabs.com). We answer within 30 days. Deleting the licence records of an active installation stops
that installation from checking its licence.

If you are in Canada, you may also complain to the Office of the Privacy Commissioner of Canada. If you are in the
European Union or the United Kingdom, you may complain to your local data protection authority.

## Children

SIGMA is a professional tool. It is not meant for children under 16, and we do not knowingly collect their
information.

## Changes

If we change this policy, we update the date at the top. If a change matters, we also announce it in the
software's update notice.
