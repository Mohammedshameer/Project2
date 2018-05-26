from django.shortcuts import render

from django.http import HttpResponse
from .models import Board


def homePageView(request):
    boards = Board.objects.all()
    return render(request, 'homePageView.html', {'boards': boards})
# Create your views here.
