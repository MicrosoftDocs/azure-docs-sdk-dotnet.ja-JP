<Type Name="RegenerateCredentialParameters" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.RegenerateCredentialParameters">
  <TypeSignature Language="C#" Value="public class RegenerateCredentialParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegenerateCredentialParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.RegenerateCredentialParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RegenerateCredentialParameters" />
  <TypeSignature Language="F#" Value="type RegenerateCredentialParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e55bc-101">ログインに資格情報を再生成するために使用するパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="e55bc-101">The parameters used to regenerate the login credential.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegenerateCredentialParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegenerateCredentialParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e55bc-102">RegenerateCredentialParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e55bc-102">Initializes a new instance of the RegenerateCredentialParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegenerateCredentialParameters (Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegenerateCredentialParameters.#ctor(Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As PasswordName)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.RegenerateCredentialParameters : Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.RegenerateCredentialParameters" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.RegenerateCredentialParameters name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e55bc-103">パスワードを再生成 - パスワードまたは password2 の名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="e55bc-103">Specifies name of the password which should be regenerated -- password or password2.</span></span> <span data-ttu-id="e55bc-104">使用可能な値が含まれます: 'password'、'password2'</span><span class="sxs-lookup"><span data-stu-id="e55bc-104">Possible values include: 'password', 'password2'</span></span></param>
        <summary>
            <span data-ttu-id="e55bc-105">RegenerateCredentialParameters クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e55bc-105">Initializes a new instance of the RegenerateCredentialParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegenerateCredentialParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As PasswordName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegenerateCredentialParameters.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ContainerRegistry.Models.PasswordName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e55bc-106">取得または設定したパスワードを再生成 - パスワードまたは password2 の名前を指定します。</span><span class="sxs-lookup"><span data-stu-id="e55bc-106">Gets or sets specifies name of the password which should be regenerated -- password or password2.</span></span> <span data-ttu-id="e55bc-107">使用可能な値が含まれます: 'password'、'password2'</span><span class="sxs-lookup"><span data-stu-id="e55bc-107">Possible values include: 'password', 'password2'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegenerateCredentialParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="regenerateCredentialParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e55bc-108">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="e55bc-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e55bc-109">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="e55bc-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>