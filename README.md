# Next.js Dynamic Route Error with Special Characters

This repository demonstrates a common but easily overlooked error in Next.js applications involving dynamic routes with special characters.  When using `getServerSideProps` or `getStaticProps` with routes containing spaces or other non-alphanumeric characters, the data fetching process might fail if not handled appropriately.

The `bug.js` file showcases the incorrect implementation that leads to errors.  The `bugSolution.js` file demonstrates the corrected approach.

## How to Reproduce

1. Clone the repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to the incorrect route in your browser (as defined in the code). You should observe an error.
5. Then, test the correct route provided in the solution.