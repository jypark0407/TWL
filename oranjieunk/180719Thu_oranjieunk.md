# �ؽ�Ʈ ��/�ڷ� ������ ����
text.strip()
# \n�� \r�� �������� ����
text.replace('\n','').replace('\r','')

���� ���� �ܿ����Ƿ� �ܿ�� ���� �δ� ������ ����!
��,���� ���� �ϰ� �Ǵ� ��� �Լ��� �����(�������� 1�� �̻� �����ϸ� �Լ� ����)
ToDo ����Ʈ �����
�ǹ����� ������ ������ ���� ����, ���ҽ� ����, �䱸���� ���� �� �پ��� ������ ���� ��ȹ�� ������ ��� �������� ���ϰ� ������ ��, 
so �۾��� ������ �� ������ �߰��� ���ߴ��� �߿��� �κ��� �Ϸ�� �� �ֵ��� �ϰ�, �߰� ����� ���� �����ϴ� ���� �߿�
��ü�� ������������ �м� �����ϱ�
�ð��� ���� ���̵� ���ϱ� ���� ������
dom -> html ������Ʈ
������ Ŭ��¡�� ��ü �ð� 80%�� �Ҹ�
�ڵ��� �Ƹ��ٿ��� �Ű澲�� ������� �ϳ��� �Լ��� 5���� ���� �ʵ��� ����
�� �Լ��� TMI���� �ʰ� �ʿ��� �κи� �����ϰ� �ؼ� �ٸ� ������ ���� ������ ��

<CSS>
������Ʈ ������: p �� �±� �̸��� p�� ������Ʈ
<p id="welcome">�ֶ��̳� å�濡 ���� ���� ȯ���մϴ�.</p>
<p class="highlight">������ �����ϼ���.</p>

���̵� ������: #welcome �� id �Ӽ��� welcome�� ������Ʈ
<p id="welcome">�ֶ��̳� å�濡 ���� ���� ȯ���մϴ�.</p>

Ŭ���� ������: .highlight �� class �Ӽ��� highlight�� ������Ʈ
<p class="highlight">������ �����ϼ���.</p>
<li class="highlight">��ȭ</li>


* �������� ����
p.highlight �� �±� �̸��� p�̸鼭 class �Ӽ��� highlight�� ������Ʈ
<p class="highlight">������ �����ϼ���.</p>

body .highlight �� �±� �̸��� body�� ������Ʈ�� �ڼ�(descendents) �� class �Ӽ��� highlight�� ������Ʈ
<p class="highlight">������ �����ϼ���.</p>
<li class="highlight">��ȭ</li>

body > .highlight �� �±� �̸��� body�� ������Ʈ�� �����ڽ�(immediate children) �� class �Ӽ��� highlight�� ������Ʈ
<p class="highlight">������ �����ϼ���.</p>



���� �˻��� �ڿ��� ó���� �ȵǾ �ܾ� ���� �˻��ص� ��