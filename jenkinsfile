provider "aws" {
    region = "ap-south-1"
}
resource "aws_instance" "server"{
    ami ="ami-0af9569868786b23a"
    instance_type = "t2.micro"
    key_name= "com4.pem"
    tags = {
        name ="terraform server"
    }
}
