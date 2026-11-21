# TypeScript Mastery Challenge – Cinema Booking

**Prepared by:** Abdelrahman Maarouf
**Course:** Learn TypeScript in Arabic 2022 – Lessons #01 to #15

---

## Description

This challenge tests your **full understanding** of **"Learn TypeScript in Arabic 2022"** lessons **#01 to #15**.

You will build a **console-based Cinema Booking** program using:
- VS Code + Terminal
- `tsc --watch`
- Strict type checking
- All concepts from the 15 lessons

---

## Concepts Covered

- **Setup and Intro (#01–#04)**
  - Install TypeScript, `tsc`, `tsconfig.json`, watch mode
  - Static vs Dynamic typing
- **Types and Variables (#05)**
  - Type annotations, type inference, `any`
- **Arrays (#06–#07)**
  - Typed arrays, multidimensional arrays
- **Functions (#08–#11)**
  - Parameter and return annotations, optional / default / rest parameters, arrow and anonymous functions
- **Type Aliases (#12–#13)**
  - Simple aliases, advanced aliases (objects, unions, intersections `&`)
- **Literal Types (#14)**
  - Restricting values to exact strings/numbers
- **Tuples (#15)**
  - Fixed-length typed arrays

---

## Project Structure

```
/TypeScript-Cinema-Challenge
│
├─ src/
│   ├─ variables.ts       # #05, #14
│   ├─ arrays.ts          # #06–#07
│   ├─ functions.ts       # #08–#11
│   ├─ typeAliases.ts     # #12–#13
│   ├─ tuples.ts          # #15
│   └─ main.ts            # Cinema Booking System
│
├─ dist/                  # Auto-generated
├─ tsconfig.json
└─ README.md
```

---

## Task Instructions

### 1. Setup (#01–#04)

```bash
npm install -g typescript
tsc --init
```

Edit `tsconfig.json`:

```json
{
  "compilerOptions": {
    "strict": true,
    "outDir": "./dist",
    "rootDir": "./src",
    "target": "ES2020",
    "module": "commonjs"
  }
}
```

> **Note on Modules:** Keep `export {}` at the bottom of practice files (`variables.ts`, `arrays.ts`, `functions.ts`, `tuples.ts`) so TypeScript treats each file as an isolated module and prevents variable name collisions across files.

---

### 2. Complete Each File

#### `src/variables.ts`
```ts
// TODO #1: Declare cinemaName (string), screenCount (number), isOpen (boolean)
// TODO #2: Use `any` once and explain in a comment why to avoid it
// TODO #3: Declare a literal type variable: 'standard' | 'vip' | 'imax'

export {};
```

#### `src/arrays.ts`
```ts
// TODO #4: Create movies: string[]
// TODO #5: Create seats: ('free' | 'taken')[][]  (a 3 x 4 grid)
// TODO #6: Use push and pop on movies

export {};
```

#### `src/functions.ts`
```ts
// TODO #7: Function with a return type: calculateTotal(price: number, quantity: number): number
// TODO #8: Function with an optional parameter and a default parameter
// TODO #9: Function with a rest parameter (...prices: number[])
// TODO #10: Arrow function used inside forEach to print items

export {};
```

#### `src/typeAliases.ts`
```ts
// TODO #11: Simple type alias: export type SeatStatus = 'free' | 'taken'
// TODO #12: Object type alias: export type Movie = { title: string; duration: number; ticketPrice: number }
// TODO #13: Advanced type alias using intersection (&):
//           export type VipMovie = Movie & { has3DGlasses: boolean; loungeAccess: boolean }
```

#### `src/tuples.ts`
```ts
// TODO #14: Create a tuple [string, number, boolean] representing [movieTitle, seatNumber, isPaid]
// TODO #15: Create a function that returns a tuple: [string, number]

export {};
```

---

### 3. Main Program: `src/main.ts`

```ts
// TODO #16: Add a comment showing one error that static typing catches and dynamic JavaScript would not

// TODO #17: Import SeatStatus, Movie, and VipMovie from './typeAliases'

// TODO #18: Declare:
//           - seats: SeatStatus[][] (a 3 x 4 grid initialized as 'free')
//           - movies: Movie[] (at least 3 movies)
//           - vipMovie: VipMovie
//           - bookingSummary: [number, number]  (representing [bookedCount, freeCount])

// TODO #19: Write bookSeat(row: number, seat: number, customerName?: string): boolean
//           - Check if row and seat are within bounds and the seat is 'free'
//           - Mark the seat as 'taken', log a confirmation message, and return true
//           - Otherwise log a warning message and return false

// TODO #20: Write bookMultipleSeats(...positions: [number, number][]): void
//           - Loop through positions using forEach with an arrow function and call bookSeat

// TODO #21: Write getSummary(): [number, number]
//           - Count 'taken' and 'free' seats in the grid and return [booked, free] as a tuple

// TODO #22: Run the demo:
//           - Book 1 single seat using bookSeat
//           - Book 3 seats at once using bookMultipleSeats
//           - Try booking an already 'taken' seat to verify validation
//           - Print the updated seat grid and the bookingSummary tuple
```

---

### 4. Testing

```bash
tsc --watch
node dist/main.js
```

The output must show:
- Confirmation messages for booked seats and a warning for already taken seats
- The updated `3 x 4` seat grid
- The final summary tuple `[booked, free]`

---

### 5. README.md

Add the following to your repository `README.md`:
- Your name
- **What is TypeScript?** (2–3 sentences in your own words explaining static typing vs dynamic typing)
- Screenshot showing **no compile errors** in the terminal
- Screenshot of the program output

---

## Evaluation (100 Points)

| Points | Criteria |
|:---:|---|
| 15 | Setup, `tsconfig.json`, and zero compile errors |
| 15 | Variables, `any` explanation, and literal types |
| 15 | Arrays and 2D seat grid manipulation |
| 20 | Functions: return types, optional/default/rest parameters, arrow functions |
| 15 | Type aliases (union, object, and intersection `&`) |
| 20 | Tuples and complete booking logic in `main.ts` |
| +Bonus | Ticket price calculation with VIP surcharge, seat grid formatting |

---

## Author
- Abdelrahman Maarouf