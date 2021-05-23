# devopstraining


resource "aws_subnet" "main" {
  vpc_id     = 
  cidr_block = var.mainVPCsubnetcidr

  tags = {
    Name = "Main"
  }
}