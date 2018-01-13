<Type Name="MobileServiceConflictException" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException">
  <TypeSignature Language="C#" Value="public class MobileServiceConflictException : Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceConflictException extends Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceConflictException&#xA;Inherits MobileServiceInvalidOperationException" />
  <TypeSignature Language="F#" Value="type MobileServiceConflictException = class&#xA;    inherit MobileServiceInvalidOperationException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="97149-101">'競合' のステータス コードでの http 応答の詳細についてを説明します。</span><span class="sxs-lookup"><span data-stu-id="97149-101">Provides details of http response with status code of 'Conflict'</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceConflictException (Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException source, Newtonsoft.Json.Linq.JObject value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException source, class Newtonsoft.Json.Linq.JObject value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException.#ctor(Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As MobileServiceInvalidOperationException, value As JObject)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException : Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException * Newtonsoft.Json.Linq.JObject -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException (source, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
        <Parameter Name="value" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="source">
            <span data-ttu-id="97149-102">内部例外。</span><span class="sxs-lookup"><span data-stu-id="97149-102">The inner exception.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="97149-103">競合が発生したサーバーから現在のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="97149-103">The current instance from the server that the conflict occurred for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="97149-104"><see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="97149-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceConflictException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>