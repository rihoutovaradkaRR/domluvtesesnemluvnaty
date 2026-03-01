# Deployment Design — Domluvte se s nemluvňaty

## Cíl
Nasadit statický web na internet s vlastní doménou `domluvtesesnemluvnaty.cz`.

## Přístup
GitHub → Cloudflare Pages (automatické nasazení při každém `git push`)

## Provedené kroky
- [x] Přejmenování `index-v3.html` → `index.html`
- [x] Přidán `.gitignore`, odstraněn `.DS_Store`
- [x] Repozitář propojen s Cloudflare Pages
- [x] Nameservery změněny na Cloudflare (Active24 → Cloudflare)

## Zbývá
- [ ] Po propagaci DNS: přidat vlastní doménu v Cloudflare Pages → Custom domains → `domluvtesesnemluvnaty.cz`

## Technické detaily
- Hosting: Cloudflare Pages (free tier)
- Repozitář: github.com/rihoutovaradkaRR/domluvtesesnemluvnaty
- Větev: main
- Build: žádný (statický HTML/CSS)
