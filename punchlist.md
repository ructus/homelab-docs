# Homelab Network and Diagram Documentation Punch List

1. [ ] Review Markdown encoding artifacts later. Suspected mojibake examples currently render correctly in the Markdown files and Zensical pages, so skip cleanup for now. Recheck if characters such as `Ãƒ`, `Ã¢`, or broken symbols appear in rendered docs during future network or hardware edits.

2. [ ] Keep application diagrams separate for now. Since detailed application diagrams and software lists are intentionally not complete yet, avoid trying to fully diagram every app in this pass. Only update app references that affect network truth: DNS names, ingress IPs, host IPs, reverse proxy paths, and physical/VM placement.

3. [ ] Reconcile `bearing-zero.com` DNS export with network inventory. Add all current A records from the DNS01 zone export, including service aliases, owner/platform, and whether each name is canonical or legacy.

4. [ ] Clean up remote image references and copied-source tracking noise. The Harbor install guide still embeds remote images with `utm_source=chatgpt.com`, and several pages use inline image styling instead of a shared docs pattern. Replace remote images with local assets or text references where appropriate, remove tracking parameters, and standardize image presentation.

5. [ ] Audit navigation coverage for orphaned or duplicate docs. Compare `zensical.toml` navigation against the docs tree, especially Ansible pages such as `ansible-k3s-reboot.md`, backup/operations pages, and reference material. Add useful pages to nav, merge duplicates, or mark stale pages as archived.

6. [ ] Periodically audit documentation tags for drift. Check for one-off tags, duplicate meanings, capitalization inconsistencies, and pages with too many or too few tags after major documentation updates.

7. [ ] Urgently clean up secret material in reference notes. `docs/reference/random-usefull-stuff.md` appears to contain real PATs, API tokens, service tokens, and other credential material. Remove secrets from the repo, rotate anything that was committed or exposed, and replace the page with redacted examples plus references to the approved secret store.

8. [ ] Consolidate overlapping standards pages. `docs/reference/standards.md` and `docs/reference/documentation-standards.md` both describe publishing conventions and review checklists. Choose one canonical standards page, merge any unique guidance, and update links/cards/navigation to point to the canonical page.

9. [ ] Review loose support assets for ownership and use. Files such as `docs/stylesheets/bak.extra.css`, Harbor `.txt` snippets, YAML examples, and Draw.io sources should either be referenced by a page, moved under a clearly named assets/examples area, or archived/removed so supporting material does not drift silently.

10. [ ] Add lightweight docs quality checks to CI. Add a script or CI step for front matter presence, tag count/format, nav coverage, broken local links, generated-output patterns, tracking parameters, and obvious secret patterns so future review findings are caught before publishing.
