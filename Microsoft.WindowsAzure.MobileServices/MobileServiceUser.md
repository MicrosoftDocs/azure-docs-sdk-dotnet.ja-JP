<Type Name="MobileServiceUser" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceUser">
  <TypeSignature Language="C#" Value="public class MobileServiceUser" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceUser extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceUser" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceUser" />
  <TypeSignature Language="F#" Value="type MobileServiceUser = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            認証済みのモバイル サービス ユーザー。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceUser (string userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceUser.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (userId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceUser : string -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceUser" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceUser userId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userId">
            正常に認証されたユーザーのユーザー id。
            </param>
        <summary>
            MobileServiceUser クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MobileServiceAuthenticationToken">
      <MemberSignature Language="C#" Value="public virtual string MobileServiceAuthenticationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MobileServiceAuthenticationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceUser.MobileServiceAuthenticationToken" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property MobileServiceAuthenticationToken As String" />
      <MemberSignature Language="F#" Value="member this.MobileServiceAuthenticationToken : string with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceUser.MobileServiceAuthenticationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            によって指定されたユーザーの Microsoft Azure Mobile Services の認証トークン、<see cref="P:Microsoft.WindowsAzure.MobileServices.MobileServiceUser.UserId" />です。 Null 以外の場合、認証トークンが認証されたユーザー レベル権限が必要な Microsoft Azure モバイル サービスですべての操作を実行できるように、Microsoft Azure モバイル サービスに加えられたすべての要求に含まれます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public virtual string UserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceUser.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property UserId As String" />
      <MemberSignature Language="F#" Value="member this.UserId : string with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceUser.UserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または正常に認証されたユーザーのユーザー id を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>