# Kshitij Inventory Management PWA

**Full-featured inventory system** for multi-location, multi-warehouse use.

### Key Features
- Real-time stock tracking across multiple warehouses
- Batch numbers and expiry dates
- Damages, returns, and claims tracking
- Physical vs system stock reconciliation (Stocktake)
- Automatic replenishment suggestions based on sales
- Receive inventory from purchase invoices (with mismatch alerts)
- Sales and purchase returns (automatically adjust stock)
- Waybill / invoice mismatch tracking (add custom fields)
- CSV import and export for inventory
- Works great as PWA on tablets/phones

### How to Run
1. On a Windows/Mac/Linux computer with Docker installed:
   - Clone or download this repository
   - Put all files in one folder
   - Open terminal/command prompt in that folder
   - Run: `docker compose up -d`
2. Wait 1-2 minutes
3. Open browser → http://localhost:8000 (or your PC IP:8000)
4. On your Lenovo Tab P12:
   - Open Chrome → type the server URL
   - Tap menu → "Add to Home screen" → works like an app
   - Or install official **InvenTree** app from Play Store and connect to the URL

### First Setup After Running
- Login and create your Warehouses / Locations
- Add Parts with Batch + Expiry enabled
- Use Purchase Orders to receive stock (mismatch shown)
- Use Return Orders for sales/purchase returns
- Run Stocktake for reconciliation
- Set minimum stock levels for replenishment alerts

**Security note:** Change the passwords in `.env` and `docker-compose.yml` before starting.

Enjoy your powerful inventory system!
