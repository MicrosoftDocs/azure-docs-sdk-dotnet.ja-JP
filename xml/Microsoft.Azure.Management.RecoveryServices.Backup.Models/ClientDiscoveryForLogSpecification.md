<Type Name="ClientDiscoveryForLogSpecification" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification">
  <TypeSignature Language="C#" Value="public class ClientDiscoveryForLogSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientDiscoveryForLogSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientDiscoveryForLogSpecification" />
  <TypeSignature Language="F#" Value="type ClientDiscoveryForLogSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7ba0e-101">Json のクライアントの探索で靴箱ログ仕様を表すクラスです。</span><span class="sxs-lookup"><span data-stu-id="7ba0e-101">Class to represent shoebox log specification in json client discovery.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientDiscoveryForLogSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7ba0e-102">ClientDiscoveryForLogSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7ba0e-102">Initializes a new instance of the ClientDiscoveryForLogSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientDiscoveryForLogSpecification (string name = null, string displayName = null, string blobDuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string blobDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional blobDuration As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification : string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification (name, displayName, blobDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="blobDuration" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7ba0e-103">name</span><span class="sxs-lookup"><span data-stu-id="7ba0e-103">Name</span></span></param>
        <param name="displayName"><span data-ttu-id="7ba0e-104">ローカライズされた表示名</span><span class="sxs-lookup"><span data-stu-id="7ba0e-104">Localized display name</span></span></param>
        <param name="blobDuration"><span data-ttu-id="7ba0e-105">blob の期間</span><span class="sxs-lookup"><span data-stu-id="7ba0e-105">blob duration</span></span></param>
        <summary>
            <span data-ttu-id="7ba0e-106">ClientDiscoveryForLogSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="7ba0e-106">Initializes a new instance of the ClientDiscoveryForLogSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobDuration">
      <MemberSignature Language="C#" Value="public string BlobDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification.BlobDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobDuration As String" />
      <MemberSignature Language="F#" Value="member this.BlobDuration : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification.BlobDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobDuration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7ba0e-107">取得または blob 期間の設定</span><span class="sxs-lookup"><span data-stu-id="7ba0e-107">Gets or sets blob duration</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7ba0e-108">取得またはローカライズされた表示名を設定</span><span class="sxs-lookup"><span data-stu-id="7ba0e-108">Gets or sets localized display name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ClientDiscoveryForLogSpecification.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7ba0e-109">取得または設定の名前</span><span class="sxs-lookup"><span data-stu-id="7ba0e-109">Gets or sets name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>