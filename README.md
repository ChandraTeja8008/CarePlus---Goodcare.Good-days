# CarePlus

CarePlus is a responsive healthcare appointment-booking demo built with React,
Vite, and Express. It includes a clinic landing page, doctor search and
specialty filters, provider cards, and an appointment request form.

## Requirements

- Node.js 18 or newer
- npm

## Run locally

Install the root, client, and server dependencies:

```powershell
npm.cmd install
npm.cmd install --prefix client
npm.cmd install --prefix server
```

Start the API and frontend together from the project root:

```powershell
npm.cmd run dev
```

Open the frontend at <http://127.0.0.1:5173>. The API health endpoint is
available at <http://127.0.0.1:5000/api/health>.

## Demo booking behavior

Provider details are sample content. Booking requests are saved in the current
browser's local storage; they are not sent to a clinic or stored by the API.
