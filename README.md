# AI chat UI prototypes

Two chat-first prototypes. Each opens on a centered search box and splits into chat plus a results panel after the first search. Both are single static HTML files with sample data and no build step.

- **Moonlit Market** (shopping): https://vikas-oplify.github.io/ai-ui/
- **Roost** (PGs, shared flats and whole flats for bachelors): https://vikas-oplify.github.io/ai-ui/roost/

## Moonlit Market

A prototype of an AI shopping chat. It opens on a centered search box. After a search, the screen splits: chat on the left, product results on the right.

### Features
- Animated "thinking" steps, then the results panel slides in
- Grid or list view, filters, sorting, and a short AI summary
- Product detail with why it fits, its main drawback, specs, and a 90-day price chart
- Compare 2–3 products as a table in the chat
- Follow-ups like "under 5k", "cheaper", "top rated" refine the current results
- Drag the divider to resize, or expand the panel; full-screen panel on phones
- Cart with count and total

The catalogue is made-up sample data. It's a single static `index.html` with no build step.

## Roost

A rental finder for bachelors, at `roost/index.html`.

### Features
- Save your college, office or home in chat. Roost checks the locality against the pincode and asks you to clarify when they don't match or the address is vague.
- Every listing shows the walk or auto time to your saved place
- Listings show the true monthly cost, move-in cost, red flags, house rules, flatmates and bachelor-friendly status
- Map tab with price pins and 1 km / 2 km rings
- Move-in checklist that ticks itself as you search, book visits and finalise
- Finalising a place opens a rent agreement draft with stamp duty estimates for Maharashtra and Karnataka
- Follow-ups for police verification, movers and splitting costs

Covers Powai (IIT Bombay), Koramangala and Hinjewadi with made-up listings. Stamp duty figures are rough estimates.
