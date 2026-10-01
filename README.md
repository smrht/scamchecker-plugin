# Scamchecker voor Claude

Laat Claude een verdachte mail, sms, WhatsApp-bericht, link of screenshot nakijken met [scamchecker.nl](https://scamchecker.nl). Je krijgt het oordeel terug met de verdachte stukken en wat je nu doet. Een uitslag zonder rode vlaggen betekent nooit dat iets veilig is.

## Claude Code

```
/plugin marketplace add smrht/scamchecker-plugin
/plugin install scamchecker@scamchecker-plugins
```

## Claude (web en desktop)

Ga naar Customize > Connectors, kies Add custom connector en vul in:

```
https://scamchecker.nl/mcp
```

Geen login nodig. In `desktop/` staat ook een Desktop Extension (.mcpb) die dezelfde server aanspreekt.

## Privacy

Berichten worden nagekeken en niet bewaard. Zie [scamchecker.nl/privacy](https://scamchecker.nl/privacy). Vragen: contact@scamchecker.nl.
