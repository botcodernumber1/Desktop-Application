namespace E_Contact
{
    partial class Econtact
    {
        /// <summary>
        ///  Required designer variable.
        /// </summary>
        private System.ComponentModel.IContainer components = null;

        /// <summary>
        ///  Clean up any resources being used.
        /// </summary>
        /// <param name="disposing">true if managed resources should be disposed; otherwise, false.</param>
        protected override void Dispose(bool disposing)
        {
            if (disposing && (components != null))
            {
                components.Dispose();
            }
            base.Dispose(disposing);
        }

        #region Windows Form Designer generated code

        /// <summary>
        ///  Required method for Designer support - do not modify
        ///  the contents of this method with the code editor.
        /// </summary>
        private void InitializeComponent()
        {
            System.ComponentModel.ComponentResourceManager resources = new System.ComponentModel.ComponentResourceManager(typeof(Econtact));
            pictureBox1 = new PictureBox();
            IblContactID = new Label();
            textboxContactID = new TextBox();
            textboxFirstName = new TextBox();
            IblFirstName = new Label();
            textboxLastName = new TextBox();
            IblLastName = new Label();
            textboxContactNumber = new TextBox();
            IblContactNumber = new Label();
            textBox5 = new TextBox();
            IblAddress = new Label();
            IblGender = new Label();
            comboBox1 = new ComboBox();
            btnAdd = new Button();
            btnUpdate = new Button();
            btnDelete = new Button();
            btnClear = new Button();
            dataGridView1 = new DataGridView();
            Search = new Label();
            textboxSearch = new TextBox();
            pictureBox2 = new PictureBox();
            ((System.ComponentModel.ISupportInitialize)pictureBox1).BeginInit();
            ((System.ComponentModel.ISupportInitialize)dataGridView1).BeginInit();
            ((System.ComponentModel.ISupportInitialize)pictureBox2).BeginInit();
            SuspendLayout();
            // 
            // pictureBox1
            // 
            pictureBox1.Image = (Image)resources.GetObject("pictureBox1.Image");
            pictureBox1.Location = new Point(325, 12);
            pictureBox1.Name = "pictureBox1";
            pictureBox1.Size = new Size(100, 50);
            pictureBox1.SizeMode = PictureBoxSizeMode.Zoom;
            pictureBox1.TabIndex = 0;
            pictureBox1.TabStop = false;
            // 
            // IblContactID
            // 
            IblContactID.AutoSize = true;
            IblContactID.BackColor = Color.Transparent;
            IblContactID.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            IblContactID.ForeColor = Color.Black;
            IblContactID.Location = new Point(43, 106);
            IblContactID.Name = "IblContactID";
            IblContactID.Size = new Size(86, 20);
            IblContactID.TabIndex = 1;
            IblContactID.Text = "Contact ID";
            IblContactID.Click += label1_Click;
            // 
            // textboxContactID
            // 
            textboxContactID.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            textboxContactID.Location = new Point(148, 103);
            textboxContactID.Name = "textboxContactID";
            textboxContactID.Size = new Size(232, 26);
            textboxContactID.TabIndex = 2;
            // 
            // textboxFirstName
            // 
            textboxFirstName.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            textboxFirstName.Location = new Point(148, 135);
            textboxFirstName.Name = "textboxFirstName";
            textboxFirstName.Size = new Size(232, 26);
            textboxFirstName.TabIndex = 4;
            // 
            // IblFirstName
            // 
            IblFirstName.AutoSize = true;
            IblFirstName.BackColor = Color.Transparent;
            IblFirstName.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            IblFirstName.ForeColor = Color.Black;
            IblFirstName.Location = new Point(43, 138);
            IblFirstName.Name = "IblFirstName";
            IblFirstName.Size = new Size(86, 20);
            IblFirstName.TabIndex = 3;
            IblFirstName.Text = "First Name";
            IblFirstName.Click += label2_Click;
            // 
            // textboxLastName
            // 
            textboxLastName.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            textboxLastName.Location = new Point(148, 167);
            textboxLastName.Name = "textboxLastName";
            textboxLastName.Size = new Size(232, 26);
            textboxLastName.TabIndex = 6;
            // 
            // IblLastName
            // 
            IblLastName.AutoSize = true;
            IblLastName.BackColor = Color.Transparent;
            IblLastName.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            IblLastName.ForeColor = Color.Black;
            IblLastName.Location = new Point(43, 170);
            IblLastName.Name = "IblLastName";
            IblLastName.Size = new Size(86, 20);
            IblLastName.TabIndex = 5;
            IblLastName.Text = "Last Name";
            IblLastName.Click += label3_Click;
            // 
            // textboxContactNumber
            // 
            textboxContactNumber.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            textboxContactNumber.Location = new Point(148, 199);
            textboxContactNumber.Name = "textboxContactNumber";
            textboxContactNumber.Size = new Size(232, 26);
            textboxContactNumber.TabIndex = 8;
            // 
            // IblContactNumber
            // 
            IblContactNumber.AutoSize = true;
            IblContactNumber.BackColor = Color.Transparent;
            IblContactNumber.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            IblContactNumber.ForeColor = Color.Black;
            IblContactNumber.Location = new Point(43, 202);
            IblContactNumber.Name = "IblContactNumber";
            IblContactNumber.Size = new Size(93, 20);
            IblContactNumber.TabIndex = 7;
            IblContactNumber.Text = "Contact No.";
            // 
            // textBox5
            // 
            textBox5.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            textBox5.Location = new Point(148, 231);
            textBox5.Multiline = true;
            textBox5.Name = "textBox5";
            textBox5.Size = new Size(232, 60);
            textBox5.TabIndex = 10;
            textBox5.TextChanged += textBox5_TextChanged;
            // 
            // IblAddress
            // 
            IblAddress.AutoSize = true;
            IblAddress.BackColor = Color.Transparent;
            IblAddress.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            IblAddress.ForeColor = Color.Black;
            IblAddress.Location = new Point(43, 234);
            IblAddress.Name = "IblAddress";
            IblAddress.Size = new Size(68, 20);
            IblAddress.TabIndex = 9;
            IblAddress.Text = "Address";
            // 
            // IblGender
            // 
            IblGender.AutoSize = true;
            IblGender.BackColor = Color.Transparent;
            IblGender.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            IblGender.ForeColor = Color.Black;
            IblGender.Location = new Point(43, 300);
            IblGender.Name = "IblGender";
            IblGender.Size = new Size(63, 20);
            IblGender.TabIndex = 11;
            IblGender.Text = "Gender";
            // 
            // comboBox1
            // 
            comboBox1.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            comboBox1.FormattingEnabled = true;
            comboBox1.Items.AddRange(new object[] { "Male", "Female" });
            comboBox1.Location = new Point(148, 298);
            comboBox1.Name = "comboBox1";
            comboBox1.Size = new Size(232, 28);
            comboBox1.TabIndex = 21;
            comboBox1.SelectedIndexChanged += comboBox1_SelectedIndexChanged;
            // 
            // btnAdd
            // 
            btnAdd.BackColor = Color.ForestGreen;
            btnAdd.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            btnAdd.ForeColor = Color.White;
            btnAdd.Location = new Point(49, 357);
            btnAdd.Name = "btnAdd";
            btnAdd.Size = new Size(100, 55);
            btnAdd.TabIndex = 22;
            btnAdd.Text = "Add";
            btnAdd.UseVisualStyleBackColor = false;
            // 
            // btnUpdate
            // 
            btnUpdate.BackColor = Color.SteelBlue;
            btnUpdate.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            btnUpdate.ForeColor = Color.White;
            btnUpdate.Location = new Point(231, 357);
            btnUpdate.Name = "btnUpdate";
            btnUpdate.Size = new Size(100, 55);
            btnUpdate.TabIndex = 23;
            btnUpdate.Text = "Update";
            btnUpdate.UseVisualStyleBackColor = false;
            // 
            // btnDelete
            // 
            btnDelete.BackColor = Color.Crimson;
            btnDelete.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            btnDelete.ForeColor = Color.White;
            btnDelete.Location = new Point(411, 357);
            btnDelete.Name = "btnDelete";
            btnDelete.Size = new Size(100, 55);
            btnDelete.TabIndex = 24;
            btnDelete.Text = "Delete";
            btnDelete.UseVisualStyleBackColor = false;
            // 
            // btnClear
            // 
            btnClear.BackColor = Color.Orange;
            btnClear.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            btnClear.ForeColor = Color.White;
            btnClear.Location = new Point(600, 357);
            btnClear.Name = "btnClear";
            btnClear.Size = new Size(100, 55);
            btnClear.TabIndex = 25;
            btnClear.Text = "Clear";
            btnClear.UseVisualStyleBackColor = false;
            // 
            // dataGridView1
            // 
            dataGridView1.AllowUserToOrderColumns = true;
            dataGridView1.ColumnHeadersHeightSizeMode = DataGridViewColumnHeadersHeightSizeMode.AutoSize;
            dataGridView1.Location = new Point(390, 137);
            dataGridView1.Name = "dataGridView1";
            dataGridView1.Size = new Size(309, 188);
            dataGridView1.TabIndex = 26;
            // 
            // Search
            // 
            Search.AutoSize = true;
            Search.BackColor = Color.Transparent;
            Search.Font = new Font("Microsoft Sans Serif", 12F, FontStyle.Regular, GraphicsUnit.Point, 0);
            Search.Location = new Point(392, 103);
            Search.Name = "Search";
            Search.Size = new Size(60, 20);
            Search.TabIndex = 27;
            Search.Text = "Search";
            Search.TextAlign = ContentAlignment.MiddleLeft;
            // 
            // textboxSearch
            // 
            textboxSearch.Location = new Point(460, 105);
            textboxSearch.Name = "textboxSearch";
            textboxSearch.Size = new Size(237, 23);
            textboxSearch.TabIndex = 28;
            // 
            // pictureBox2
            // 
            pictureBox2.BackColor = Color.Transparent;
            pictureBox2.Image = (Image)resources.GetObject("pictureBox2.Image");
            pictureBox2.Location = new Point(642, 7);
            pictureBox2.Name = "pictureBox2";
            pictureBox2.Size = new Size(58, 55);
            pictureBox2.SizeMode = PictureBoxSizeMode.StretchImage;
            pictureBox2.TabIndex = 29;
            pictureBox2.TabStop = false;
            // 
            // Econtact
            // 
            AutoScaleDimensions = new SizeF(7F, 15F);
            AutoScaleMode = AutoScaleMode.Font;
            ClientSize = new Size(800, 450);
            Controls.Add(pictureBox2);
            Controls.Add(textboxSearch);
            Controls.Add(Search);
            Controls.Add(dataGridView1);
            Controls.Add(btnClear);
            Controls.Add(btnDelete);
            Controls.Add(btnUpdate);
            Controls.Add(btnAdd);
            Controls.Add(comboBox1);
            Controls.Add(IblGender);
            Controls.Add(textBox5);
            Controls.Add(IblAddress);
            Controls.Add(textboxContactNumber);
            Controls.Add(IblContactNumber);
            Controls.Add(textboxLastName);
            Controls.Add(IblLastName);
            Controls.Add(textboxFirstName);
            Controls.Add(IblFirstName);
            Controls.Add(textboxContactID);
            Controls.Add(IblContactID);
            Controls.Add(pictureBox1);
            FormBorderStyle = FormBorderStyle.None;
            Name = "Econtact";
            Text = "E-Contact";
            Load += Econtact_Load;
            ((System.ComponentModel.ISupportInitialize)pictureBox1).EndInit();
            ((System.ComponentModel.ISupportInitialize)dataGridView1).EndInit();
            ((System.ComponentModel.ISupportInitialize)pictureBox2).EndInit();
            ResumeLayout(false);
            PerformLayout();
        }

        #endregion

        private PictureBox pictureBox1;
        private Label IblContactID;
        private TextBox textboxContactID;
        private TextBox textboxFirstName;
        private Label IblFirstName;
        private TextBox textboxLastName;
        private Label IblLastName;
        private TextBox textboxContactNumber;
        private Label IblContactNumber;
        private TextBox textBox5;
        private Label IblAddress;
        private Label IblGender;
        private Label label10;
        private ComboBox comboBox1;
        private Button btnAdd;
        private Button btnUpdate;
        private Button btnDelete;
        private Button btnClear;
        private DataGridView dataGridView1;
        private Label Search;
        private TextBox textboxSearch;
        private PictureBox pictureBox2;
    }
}
