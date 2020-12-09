module "vpc" {
    source = "tutac/terraform-gcp-vpc"
    vpc_name = "test"
    firewall_name = "http-allow"
    public-subnet1-name = "public-subnet1" 
    public-subnet2-name = "public-subnet2" 
    public-subnet3-name = "public-subnet3" 
    ip_cidr_range1 = "your range"
    ip_cidr_range2 = "your range"
    ip_cidr_range3 = "your range"
}
