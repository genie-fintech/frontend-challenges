# Take-home challenge

## Resources

- API: [Pokemon TCG](https://pokemontcg.io)
- Design:
  - file: <https://figma.fun/hIqDAm>
  - prototype: <https://figma.fun/8blDqC>

  Also available as `design.fig` in this folder, open it using <https://figma.com>.

## Requirements

- [ ] Card list:
  - [ ] Implement search/filter:
    - [ ] Name
    - [ ] Type
    - [ ] Rarity
    - [ ] Set
  - [ ] Loading/PageSize limit: `12` cards on each api call
  - [ ] Implement `Loadmore` style pagination
- [ ] Use card `price` data from `cardmarket.prices.*`
- [ ] Use card's stock from `set.total`
- [ ] Cart:
  - [ ] Display selected cards as per design
  - [ ] Quantity must be able to increase, decrease & remove. Must respect the stock left limit
  - [ ] Display total number of selected cards
  - [ ] Display total price of all the cards
  - [ ] All cards should be clearable at once from cart

---

You can use any library, plugins & styling solutions.

Make sure to provide a `README.md` on how to run and build your application.

---

## Bonus

The following are some strategies to leave us with a better impression. But remember, **they're not required**.

- Build near pixel-perfect UIs
- Responsive to any screen sizes
- Smooth & Snappy CSS Transitions
- Using Next.js
    - With `getServerSideProps` or `getStaticProps`
    - Or using `App` directory with `route` enter/leave animation
- Using React hooks
- Using TypeScript
- Well-structured and organized repository
- Commenting your code
- Writing tests
