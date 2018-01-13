<Type Name="ContainerRegistry" FullName="Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry">
  <TypeSignature Language="C#" Value="public class ContainerRegistry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerRegistry extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerRegistry" />
  <TypeSignature Language="F#" Value="type ContainerRegistry = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fcf99-101">プライベート コンテナー レジストリです。</span><span class="sxs-lookup"><span data-stu-id="fcf99-101">A private container registry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerRegistry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fcf99-102">ContainerRegistry クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fcf99-102">Initializes a new instance of the ContainerRegistry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerRegistry (string userName, string password, string registryServer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userName, string password, string registryServer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (userName As String, password As String, Optional registryServer As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry : string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry" Usage="new Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry (userName, password, registryServer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="registryServer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userName"><span data-ttu-id="fcf99-103">レジストリのサーバーにログインするユーザー名。</span><span class="sxs-lookup"><span data-stu-id="fcf99-103">The user name to log into the registry server.</span></span></param>
        <param name="password"><span data-ttu-id="fcf99-104">レジストリのサーバーへのログイン パスワードです。</span><span class="sxs-lookup"><span data-stu-id="fcf99-104">The password to log into the registry server.</span></span></param>
        <param name="registryServer"><span data-ttu-id="fcf99-105">レジストリの URL です。</span><span class="sxs-lookup"><span data-stu-id="fcf99-105">The registry URL.</span></span></param>
        <summary>
            <span data-ttu-id="fcf99-106">ContainerRegistry クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fcf99-106">Initializes a new instance of the ContainerRegistry class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcf99-107">取得またはレジストリ サーバーへのログイン パスワードを設定します。</span><span class="sxs-lookup"><span data-stu-id="fcf99-107">Gets or sets the password to log into the registry server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistryServer">
      <MemberSignature Language="C#" Value="public string RegistryServer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistryServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry.RegistryServer" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistryServer As String" />
      <MemberSignature Language="F#" Value="member this.RegistryServer : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry.RegistryServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="registryServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcf99-108">取得またはレジストリの URL を設定します。</span><span class="sxs-lookup"><span data-stu-id="fcf99-108">Gets or sets the registry URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fcf99-109">省略した場合、既定値は"docker.io"にします。</span><span class="sxs-lookup"><span data-stu-id="fcf99-109">If omitted, the default is "docker.io".</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry.UserName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry.UserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcf99-110">取得またはレジストリ server にログインするユーザー名を設定します。</span><span class="sxs-lookup"><span data-stu-id="fcf99-110">Gets or sets the user name to log into the registry server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerRegistry.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fcf99-111">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="fcf99-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fcf99-112">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="fcf99-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>