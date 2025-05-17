# DeployStaticWebsiteToS3Route53
Sets up static website hosting on Amazon S3 and Route 53, enabling the use of a custom website name


## Step 1: Making Route 53 the DNS service for a domain that's in use

### Step 2: Create a hosted zone
![Hosted zones](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/Hosted%20zones.png)

### Step 3: Create records
![4 records in Hosted zones](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/4%20records%20in%20Hosted%20zones.png)

## Namecheap  

### bought a custom domain from namecheap
![custom domain](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/bought%20a%20custom%20domain%20from%20namecheap.png)

### insert the dns configuration specified by Route 53
![Namecheap custom dns configuration](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/namecheap%20custom%20dns%20configuration.png)


## Step 1: Create 3 S3 Buckets

### General purpose buckets
![3 General purpose buckets](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/General%20purpose%20buckets.png)

### Static website hosting
![Static website hosting](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/Static%20website%20hosting.png)

### Edit static website hosting
![Edit static website hosting](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/Edit%20static%20website%20hosting.png)

### Static website hosting for subdomain
![Static website hosting for subdomain](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/Static%20website%20hosting%20for%20subdomain.png)

### Edit Static website hosting for subdomain
![Edit Static website hosting for subdomain](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/Edit%20static%20website%20hosting%20for%20subdomain.png)

### configure logs folder
![snapshot of logs folder belonging to logs.haditeoaws.xyz.png](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/snapshot%20of%20logs%20folder%20belonging%20to%20logs.haditeoaws.xyz.png)

### enable server access logging for root domain
![enable server access logging for root domain](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/enabled%20server%20access%20logging%20for%20root%20domain.png)

### upload index.html
![index.html](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/upload%20index.html.png)

### upload 404.html
![404.html](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/upload%20index.html.png)

### block public access for root domain
![block public access](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/block%20public%20access%20for%20root%20domain.png)

### bucket policy for root domain
![bucket policy](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/bucket%20policy%20for%20root%20domain.png)

### bucket website endpoint
![bucket website endpoint](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/bucket%20website%20endpoint%20for%20root%20domain.png)

### test domain endpoint for root domain
![test domain endpoint for root domain](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/test%20domain%20endpoint%20for%20root%20domain.png)

### add a record alias for root domain
![a record alias for root domain](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/a%20record%20alias%20for%20root%20domain.png)

### add cname for subdomain
![cname for subdomain](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/cname%20%20for%20subdomain.png)

### test the website http://haditeoaws.xyz
![snapshot haditeoaws.xyz](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/test%20the%20website%20haditeoaws.xyz.png)

### test the website http://www.haditeoaws.xyz
![snapshot www.haditeoaws.xyz](https://github.com/hadiiteo/DeployStaticWebsiteToS3Route53/blob/main/test%20the%20website%20haditeoaws.xyz.png)

## References 
https://docs.aws.amazon.com/AmazonS3/latest/userguide/website-hosting-custom-domain-walkthrough.html
https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/migrate-dns-domain-in-use.html
