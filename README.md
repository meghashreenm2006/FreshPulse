# FreshPulse — Store Operations Intelligence

**An intelligent retail analytics dashboard that helps store managers identify operational problems, prioritize corrective actions, and make data-driven decisions.**

## About the Project

FreshPulse is a web-based Store Operations Intelligence platform designed to help retail managers monitor store performance and detect issues related to sales, inventory, wastage, deliveries, and staffing.

Instead of simply displaying reports, FreshPulse helps managers understand which problems require attention first and provides actionable recommendations based on operational risk and potential business impact.

## Problem Statement

Retail store managers often deal with large amounts of operational data across multiple stores. Identifying critical issues, understanding their impact, and deciding which problem to resolve first can be time-consuming.

FreshPulse aims to simplify this process by bringing store metrics, risk detection, investigation, and recommended actions into one dashboard.

## Key Features

- **Performance Dashboard:** Monitor sales, transactions, customer footfall, inventory, wastage, and delayed deliveries.
- **Risk Detection:** Identify potential stock shortages, elevated wastage, and delivery delays.
- **Priority-Based Analysis:** Help managers identify which operational issues need attention first.
- **Store-Level Investigation:** Examine individual store performance and distinguish confirmed facts from possible explanations.
- **Actionable Recommendations:** Review suggested operational interventions.
- **Task Management:** Track tasks through Pending, Approved, Completed, or Rejected statuses.
- **Manual Data Entry:** Enter and save store records.
- **CSV Upload:** Import store data for analysis.
- **Demo Data:** Explore the interface using illustrative synthetic data.

## Technology Stack

- React 19
- TypeScript
- Vite
- Tailwind CSS
- Recharts
- Papa Parse
- React Router
- React Context API
- LocalStorage
- Vitest

## Getting Started

### Prerequisites

Install Node.js and npm on your computer.

### Installation

1. Clone the repository:

   `git clone https://github.com/meghashreenm2006/FreshPulse.git`

2. Open the project directory:

   `cd FreshPulse`

3. Install dependencies:

   `npm install`

4. Start the development server:

   `npm run dev`

5. Open the local URL displayed in your terminal.

## How It Works

1. Enter store information manually or upload a CSV file.
2. Analyze the available operational data.
3. Review performance metrics and detected risks.
4. Investigate the affected store.
5. Review recommendations and prioritize corrective actions.
6. Track operational tasks through their completion status.

## Data Storage

Saved store records and task updates use browser-based local storage. Data is not automatically synchronized across different devices or users.

## Project Objective

To make retail operations more transparent and actionable by helping managers identify critical problems, understand potential business impact, and prioritize interventions efficiently.

## Future Enhancements

- Centralized database integration
- Multi-user access and role-based permissions
- Predictive sales and inventory analytics
- Real-time store data integration
- Enhanced risk prioritization and impact estimation

## License

Apache License 2.0
