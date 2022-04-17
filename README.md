# Ex4-outputs



output "instance_ip_addr" {

  value = aws_instance.server.public_ip
}


Elements => resourceType.resourceName.attributeName

   resourceType => aws_instance
   resourceName => server
   attibuteName = Public_IP
