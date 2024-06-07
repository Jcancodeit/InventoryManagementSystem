# InventoryManagementSystem
partial class MainForm
{
    private System.ComponentModel.IContainer components = null;
    private Button btnAddProduct;

    private void InitializeComponent()
    {
        this.btnAddProduct = new System.Windows.Forms.Button();
        this.SuspendLayout();
        
        // 
        // btnAddProduct
        // 
        this.btnAddProduct.Location = new System.Drawing.Point(100, 100);
        this.btnAddProduct.Name = "btnAddProduct";
        this.btnAddProduct.Size = new System.Drawing.Size(100, 50);
        this.btnAddProduct.TabIndex = 0;
        this.btnAddProduct.Text = "Add Product";
        this.btnAddProduct.UseVisualStyleBackColor = true;
        this.btnAddProduct.Click += new System.EventHandler(this.btnAddProduct_Click);
        
        // 
        // MainForm
        // 
        this.AutoScaleDimensions = new System.Drawing.SizeF(8F, 16F);
        this.AutoScaleMode = System.Windows.Forms.AutoScaleMode.Font;
        this.ClientSize = new System.Drawing.Size(800, 450);
        this.Controls.Add(this.btnAddProduct);
        this.Name = "MainForm";
        this.Text = "Inventory Management System";
        this.ResumeLayout(false);
    }
}
