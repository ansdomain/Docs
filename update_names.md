# All Name System (ANS) Documentation

## Updating Names in the All Name System (ANS)

To update an existing domain within the All Name System, inscribe an ordinal with the updated details for your domain. Below is the format and description of each field:

### [Example Update Format](https://ordinals.com/inscription/a74a6737e957dd7e96b2af6f998154fea73ced69ddefec632c557da4cdcc742ai0)

```json
{
    "p": "ans",
    "op": "update",
    "ns": "all",
    "name": "test.all",
    "eth": "0x11111111111111111111111111111111",
    "arb": "0x22222222222222222222222222222222",
    "trx": "0x33333333333333333333333333333333",
    "sol": "0x44444444444444444444444444444444",
    "url": "https://ord.run",
    "ip": "1.1.1.1",
    "tw": "https://x.com/ord_run",
    "tg": "https://t.me/OKXOfficial_English",
    "about": "Names on Bitcoin. First is first.",
    "relay": "26482871f33f1051f450f2da9af275794c0b5f1c61ebf35e4467fb42c2813403i0"
}
```

### Field Descriptions

| Field | Description |
|-------|-------------|
| `p`   | Protocol identifier. For ANS, this should always be "ans". |
| `op`  | Operation type. For updates, this should be "update". |
| `ns`  | Namespace. For the main ANS system, this is "all". |
| `name`| The full domain name you wish to update, including the namespace suffix (e.g., "test.all"). |
| `...` | Additional fields can be added as needed. These can include predefined fields like "eth", "url", etc., or custom subdomains defined by the user. |

**After the updating inscription is completed, you need to transfer this  inscription to yourself**. You can find the reasons in the FAQ section.

## Using the ANS Website for Domain Resolutions

The All Name System (ANS) website offers a user-friendly interface to resolve domain names and retrieve associated details. Here's a step-by-step guide on how to use the website for domain resolutions:

### Basic Domain Resolution

1. **Navigate to the ANS Website**: Open your web browser and go to `https://ord.run/`.
2. **Enter the Domain Name**: In the address bar, after the `/`, type the domain name you wish to resolve. For instance, if you want to resolve the domain "test", you would enter `https://ord.run/test`.

### Resolving Subdomains

If the domain has associated subdomains, you can retrieve specific details by appending the subdomain after the domain name:

1. **Navigate to the ANS Website**: Open your web browser and go to `https://ord.run/`.
2. **Enter the Domain and Subdomain**: In the address bar, after the `/`, type the domain name followed by another `/` and then the subdomain. For example, to retrieve the Twitter link for the domain "test", you would enter `https://ord.run/test/tw`.

### What to Expect

- **No Subdomain or Invalid Subdomain**: If you don't specify a subdomain or if the subdomain you entered isn't recognized, the website will display the Bitcoin address of the domain owner.
- **URL Type Subdomain**: If the subdomain corresponds to a URL, the website will automatically redirect you to that URL. For instance, `https://ord.run/test/tw` might redirect you to a Twitter page.
- **Non-URL Type Subdomain**: If the subdomain isn't a URL, the website will show the content associated with that subdomain. For example, `https://ord.run/test/eth` might display a specific Ethereum address.

Remember, the ANS system is designed to be intuitive and user-friendly. Even if you're not tech-savvy, you can easily navigate and retrieve information using the steps above.

