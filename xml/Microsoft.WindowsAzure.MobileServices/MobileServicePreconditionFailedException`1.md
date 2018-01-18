<Type Name="MobileServicePreconditionFailedException&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class MobileServicePreconditionFailedException&lt;T&gt; : Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServicePreconditionFailedException`1&lt;T&gt; extends Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException`1" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServicePreconditionFailedException(Of T)&#xA;Inherits MobileServicePreconditionFailedException" />
  <TypeSignature Language="F#" Value="type MobileServicePreconditionFailedException&lt;'T&gt; = class&#xA;    inherit MobileServicePreconditionFailedException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="305b1-101">' Precondition Failed' のステータス コードでの http 応答の詳細についてを説明します。</span><span class="sxs-lookup"><span data-stu-id="305b1-101">Provides details of http response with status code of 'Precondition Failed'</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServicePreconditionFailedException (Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException source, T item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException source, !T item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException`1.#ctor(Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (source As MobileServiceInvalidOperationException, item As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException&lt;'T&gt; : Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException * 'T -&gt; Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException&lt;'T&gt;" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException&lt;'T&gt; (source, item)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.WindowsAzure.MobileServices.MobileServiceInvalidOperationException" />
        <Parameter Name="item" Type="T" />
      </Parameters>
      <Docs>
        <param name="source">
            <span data-ttu-id="305b1-102">内部例外。</span><span class="sxs-lookup"><span data-stu-id="305b1-102">The inner exception.</span></span>
            </param>
        <param name="item">
            <span data-ttu-id="305b1-103">前提条件が失敗しました。 サーバーから現在のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="305b1-103">The current instance from the server that the precondition failed for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="305b1-104"><see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="305b1-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public T Item { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Item" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException`1.Item" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Item As T" />
      <MemberSignature Language="F#" Value="member this.Item : 'T" Usage="Microsoft.WindowsAzure.MobileServices.MobileServicePreconditionFailedException&lt;'T&gt;.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="305b1-105">前提条件が失敗しました。 サーバーから現在のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="305b1-105">The current instance from the server that the precondition failed for.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>