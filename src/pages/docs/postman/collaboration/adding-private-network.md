---
title: "Adding to the Private API Network"
order: 66
page_id: "adding_private_network"
warning: false
contextual_links:
  - type: section
    name: "Prerequisites"
  - type: link
    name: "Collaborating in Postman"
    url: "/docs/postman/collaboration/collaboration-intro/"
  - type: link
    name: "Postman Pricing"
    url: "https://www.postman.com/pricing"

---

You can publish the APIs that the teams in your organization use internally to the Private API Network. When you publish to the Private API Network, your team can access your APIs and start working with them immediately.

![Team APIs](https://assets.postman.com/postman-docs/Internal+Network+Explore.jpg)

You can access the Private API Network from the [Dashboard](https://www.postman.com). From there, you can publish your team's finished APIs, and the members of your team can browse APIs that you have added.

### Adding your APIs

To add a private API for your team, sign in to your [Dashboard](https://www.postman.com) and click **API Network** at the top.

> Open your browser to sign in to the [Dashboard](https://www.postman.com).

![Nav bar](https://assets.postman.com/postman-docs/Network+in+nav+bar.jpg)

Click your team name at the top left.

![Team name](https://assets.postman.com/postman-docs/Add+to+API+Network.jpg)

In your team's Private API Network space, click **Add to Network**.

![Add to network button](https://assets.postman.com/postman-docs/Add+to+Network+button.jpg)

In the modal, choose the workspace the API was built in, and select the API that you want to publish. Click **Add to Network**.

![Modal](https://assets.postman.com/postman-docs/Private+API+Network+modal.jpg)

To see the published API, navigate to your team's Priavte API Network space on the [Dashboard](https://www.postman.com) and find the API in the list.

![Listed APIs](https://assets.postman.com/postman-docs/APIs+listed+in+Private+Network.jpg)

The developers building the APIs for your organization's internal use will be able to see which APIs and collections have been added to the Private API Network from your workspace.

![Published to network](https://assets.postman.com/postman-docs/Added+to+private+network.jpg)

> APIs that have already been added to the Private API Network cannot be added again. If a team member tries to add an API that already exists on the network, they will get an error message telling them that API has already been added.

#### Security

When users sign in to Postman, only the private APIs for the teams associated with their login credentials will be visible to them. Private APIs will not be discoverable or accessible to anyone who is not a part of your team.

#### Guidelines

Only APIs in which all team members have been granted "View access" can be added to the Private API Network. You will not be able to add your private APIs to the network until you have given everyone on your team at least "View" access to the API. Learn more about team [roles and permissions](/docs/postman/collaboration/roles-and-permissions/).

## Discovering and consuming private APIs

You can find the APIs that your team has added to the Private API Network by browsing through your team's Private API space on the [Dashboard](https://www.postman.com).

> Only the private APIs for the teams associated with your login credentials will be visible to you.

Sign in to the [Dashboard](https://www.postman.com) and click **API Network** at the top.

> Open your browser to sign in to the [Dashboard](https://www.postman.com).

![Nav bar](https://assets.postman.com/postman-docs/Network+in+nav+bar.jpg)

Click your team name at the top left.

![Team name](https://assets.postman.com/postman-docs/Add+to+API+Network.jpg)

Browse throught he list of your organization's private APIs.

![API list](https://assets.postman.com/postman-docs/List+of+private+APIs.jpg)

Click on an API to see details.

![API display](https://assets.postman.com/postman-docs/Private+API+display.jpg)

If you have edit access to the API, you can make chages directly from the [Dashboard](https://www.postman.com) view.

![Edit API](https://assets.postman.com/postman-docs/Private+API+gif.gif)

You can also generate a collection based on the API schema, which will make the API more human-readable. Whne you generate the collection,it will be displayed as API documentation on the [Dashboard](https://www.postman.com).

To generate a collection, click **Generate collection** in the upper right.

![Edit API](https://assets.postman.com/postman-docs/Generate+collection+button.jpg)

Name the collection and select your reason for creating the collection.

![Generation modal](https://assets.postman.com/postman-docs/Collection+generation+modal.jpg)

To view the collection, navigate to your team workspace and click **Collections**. The collection will be displayed in a list of all the collections in that workspace.

![Generated collection](https://assets.postman.com/postman-docs/Generated+collection+on+dashboard.jpg)