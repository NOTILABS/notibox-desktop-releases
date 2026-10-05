# NotiBox — apka desktop: wydania

Kanał aktualizacji apki NotiBox na macOS i Windows. Repo zawiera **tylko wydania** (zakładka Releases), bez kodu.
Kod apki: `NOTILABS/notibox-app` (prywatne). Wydania wystawia CI (`desktop.yml`, job `publish`) z tagu `desktop-vX.Y.Z`.

- **macOS:** podpisane Developer ID i notaryzowane. Apka aktualizuje się sama (electron-updater czyta `latest-mac.yml` z najnowszego wydania).
- **Windows:** instalator do pobrania ręcznie. Dopóki instalator nie jest podpisany, wydanie nie zawiera `latest.yml`, więc apka na Windows nie aktualizuje się sama.

Nie wrzucaj tu plików ręcznie: wydanie bez weryfikacji podpisu zepsułoby aktualizacje u wszystkich.
