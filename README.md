# first_try
resource "null_resource" "example" {
  provisioner "local-exec" {
    command = "echo 'Terraform run executed successfully!'"
  }
}
