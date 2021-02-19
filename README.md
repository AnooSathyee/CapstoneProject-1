# Capstone 1 - Inventory Management System User Interface (UI)

Your task is to Build an Inventory Management for the business of your choice.  It can be for a grocery store, a car dealership, a jewelry shop, a cell phone store, a book store, or any other legitimate business that maintains an inventory.  One limitation is that the business should not contain any content that is potentially ethically offensive or graphic (drugs, sexuality, etc.)  Take some time to plan out your strategy for completing this project.  As the saying goes, <i>"If you fail to plan, you plan to fail."</i>

In the root of this repository, you will find a a pdf file outlining a methodology to approaching & solving any problem.  The file is called : <code>"Polya's Problem Solving Framework.pdf"</code>  Feel free to research and learn more about the framework online, or simply use the .pdf file as a primary reference.

Before you dive into coding, follow the steps of Prolem Solving framework, and document the steps you will be taking for this project in the <code>UPER.md</code> file.

As part of your planning process, you may want to look into some UX design tools, otherwise known as "wireframing" tools.
A few examples are : 

* <code>Figma</code> 
* <code>Sketch</code>
* <code>Balsamiq</code>
* <code>Omni Graffle</code>
* <code>Mockplus</code>
* <code>Adobe XD</code>

******************************************
<h2>
    Minimum Viable Product (MVP)
</h2>

The App must be a Single Page Application (SPA) created using the `React.js`framework as well as `react-router`.  

<h2>
    Core Functionality:
</h2>

- A Product Page View that displays Products with a thumbnail image
- A Shopping Cart View that allows for Purchase Functionality
- A Product Detail View that displays details of the product with the following details : 
  - Product Name
  - Serial Number
  - Price
  - Manufacturer (Optional, especially if there is only 1 manufacturer for **all** products)
  - Category / Tag
  - Quantity
  - Product Image
- Search Functionality
- Inventory of at least 10 items

For this project, no backend database is required.  You can simply store all your "inventory data" in a simple `.json` file, 
initialized in React State, [local storage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage), [Dexie.db](https://dexie.org/) or in any way that is easist for you to 
store the inventory data.

<h2>
    Advanced Functionality :
</h2>

- Deploy React App using any Hosting solution ([Surge](https://daveceddia.com/deploy-create-react-app-surge/), [Vercel](https://vercel.com/guides/deploying-react-with-vercel-cra), [Netlify](https://www.netlify.com/blog/2016/07/22/deploy-react-apps-in-less-than-30-seconds/), [AWS](https://aws.amazon.com/getting-started/hands-on/build-react-app-amplify-graphql/module-one/?e=gs2020&p=build-a-react-app-intro), [Heroku](https://blog.heroku.com/deploying-react-with-zero-configuration), etc. )
- Staff View - Protected Route
  - Modify Inventory Quantities (which update the inventory data)
  - Add New Products
  - Remove Products
  - Update Product details
- Staff Login View - (to allow access to the Staff View)
- Search functionality by any of the item details (serial,price,manufacturer,category)
- Allow customers to purchase multiple quantities of the same item.
- Integrate with a 3rd party payment processing tool (Stripe / Paypal)
- Error Handling when customers attempt to purchase more than what is currently available
- Error Handling when customers search for something that is not in the inventory

## ********************************************************
## Git Instructions

- [ ] Create a template copy of this repository by clicking : "Use this template"
- [ ] Name the repository the same name as the master template repository.  
- [ ] Add your TM as collaborator
- [ ] Clone YOUR repo to your local computer
- [ ] Create a new branch: <code>git checkout -b `<firstName-lastName>`</code>.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push all of your commits: <code>git push origin `<firstName-lastName>`</code>.
- [ ] When ready for your TM to review, open a Pull Request (PR) and add your TM as a collaborator.

## ********************************************************

