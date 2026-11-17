# CloudDrop: design record

## Purpose

Share and manage files through a Telegram bot with links, QR codes and expiry controls.

## Elements

| Element | Documentation boundary |
| :-- | :-- |
| Telegram request | Included in the stated project scope. Implementation details need the corresponding source or design file. |
| Bot command handling | Included in the stated project scope. Implementation details need the corresponding source or design file. |
| Drive storage | Included in the stated project scope. Implementation details need the corresponding source or design file. |
| Share link | Included in the stated project scope. Implementation details need the corresponding source or design file. |
| Expiry control | Included in the stated project scope. Implementation details need the corresponding source or design file. |

## Technical stack

- Telegram
- Google Drive
- OAuth
- QR codes

## Boundaries

OAuth grants, bot tokens, Drive credentials and private share links must be supplied through private configuration. A generated QR code does not change the access rules of its target file. Confirm expiry at the file and link layer.

## Decisions to recover

Record each design decision with its problem, selected option, rejected options and supporting artifact. Keep the original model or source revision with the record.
