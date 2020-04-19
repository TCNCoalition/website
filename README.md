# TCN Coalition website

## A Global Coalition for Privacy-First Digital Contact Tracing Protocols to Fight COVID-19

This page is currently work in progress. Your pull requests are welcome, please take a look at "How to Contribute".

## Adding your organization as a member

You can add your organization as a member of TCN by adding the informations on the `data/members.yaml` file. 

Example:

```yaml
- organization: <Name of organisation>
  country: <Country your organisation is located>
  logo: images/members/<yourimage>.png
  url: https://<domain>.<tdl>
```

### Logo

You can add your logo under ``static/images/members``. You can choose between different file types (jpg, gif, png, svg) but we recomment you to use svg. Please use a square logo with the 1:1 dimming


## How to Contribute

The following steps make it easy to contribute to this Repository and test the Webpage localy befor your make your pull request. 

### Step 1

Install [hugo](https://gohugo.io/getting-started/installing/) there is a binary file for all the popular distributions like Windows, Mac and off course Linux. 

### Step 2 

Then clone the source branch from this repository to your local device

```bash
git clone --single-branch --branch master https://github.com/TCNCoalition/website.git
```

## Step 3

Now you can switch inside the Folder and start hugo in server mode to provite a preview of the Webpage under http://localhost:1313

```bash
cd ito-org.github.io
hugo server
```