from django.db import migrations, models


class Migration(migrations.Migration):

    dependencies = [
        ('request', '0008_alter_request_response_choices'),
    ]

    operations = [
        migrations.AddIndex(
            models.Index(fields=['-time'], name='request_request_time_e49024_idx'), 
            models.Index(fields=['-time', 'user'], name='request_request_time_ab62f2_idx'),
            models.Index(
                fields=['user', 'is_secure', 'is_ajax', 'response', '-time'],
                name='request_request_user_id_5ccb65_idx',
            ),
        ),
    ]
