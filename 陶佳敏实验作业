                                  综合性实验  学生选课系统设计
实验目的:
能够基本掌握GUI窗体，包括菜单、输入输出组件、按钮、
画板、窗口和对话框等。
能够使用JComponent类组件，并掌握事件编程的方法。
分析学生选课系统。
使用GUI窗体及其组件设计窗体界面。
完成学生选课过程业务逻辑编程。
基于文件保存并读取数据。
对程序中的异常进行处理。

实验要求：
系统角色分析及类设计。学校有“人员”，分为“教师”和“学生”，教师教授“课程”，学生选择课程。
设计GUI窗体，支持学生注册、课程新加、学生选课、学生退课、打印学生选课列表等操作。
基于事件模型对业务逻辑编程，实现在界面上支持上述操作。
针对操作过程中可能会出现的各种异常，做异常处理
基于输入/输出编程，支持学生、课程、教师等数据的读写操作。

实验过程：
1.在选课系统的基础上添加GUI窗体
2.写一个浮动布局的学生选课系统的界面，上面有文本框“请输入姓名”和“请输入密码”还有一个确定单选按钮。
3.点击确定之后进入到学生选课界面，有单选框，可以选择课程，只能选择一门。
4.选完课程后，选择性别之后可以点击确定按钮和取消选课的按钮，点击确定之后提示选课成功。

核心代码：
private void addListener() {
		bt1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				if (text1.getText().equals("123")
						&& text2.getText().equals("123")) {
					new MainWindow();
					dispose();
				} else {
					JOptionPane.showMessageDialog(null, "登陆密码错误");
				}
			}
		});

		bt2.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				dispose();
			}
		});
    
    public void actionPerformed(ActionEvent e) {

		JButton bt = (JButton) e.getSource();
		// 移除上一个面板
		if (bt != null) {
			this.remove(panel2);
			this.remove(panel);
		}
		if (bt.getText().equals("查询课程")) {
			panel = new JPanel();
			panel.setLocation(100, 20);
			this.add(panel);
			this.repaint();
		}

		else {
			if (bt.getText().equals("添加课程")) {
				panel = new JPanel();
				panel.setLocation(100, 20);
				this.add(panel);
				this.repaint();
			}

			else {
				if (bt.getText().equals("退选课程")) {
					panel = new JPanel();
					panel.setLocation(100, 20);
					this.add(panel);
					this.repaint();
				}

				else {
					if (bt.getText().equals("修改课程")) {
						panel = new JPanel();
						panel.setLocation(100, 20);
						this.add(panel);
						this.repaint();


运行截图：


编程感想：
本次实验是一次综合性的实验，也是最难的一次实验，里面包含了这学期讲过的所有知识点，
虽然这次实验好多内容还不是很明白，好多知识点还是问同学才完成的，但是这次实验
却进一步提高了我的编程能力，让我进一步了解和熟悉了JAVA语言，虽然在做实验的过程
很辛苦，但是却收获很多讲述Java语言的数据结构和语法规则；基本控制结构和编程技巧；
Java语言面向对象的特点、编程方法和程序设计思路,Java语言的GUI程序
和文件及I/O流的编程方法.我也发现了自己的很多不足，做到了程序的基本运行。
学会的只是一些最简单的皮毛实，必须通过以后的编程来提高自己的能力。
