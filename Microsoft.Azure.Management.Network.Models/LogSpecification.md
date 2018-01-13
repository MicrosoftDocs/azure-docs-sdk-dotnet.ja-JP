<Type Name="LogSpecification" FullName="Microsoft.Azure.Management.Network.Models.LogSpecification">
  <TypeSignature Language="C#" Value="public class LogSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LogSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.LogSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class LogSpecification" />
  <TypeSignature Language="F#" Value="type LogSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="40a2d-101">ログ記録の仕様の説明です。</span><span class="sxs-lookup"><span data-stu-id="40a2d-101">Description of logging specification.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LogSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.LogSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="40a2d-102">LogSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="40a2d-102">Initializes a new instance of the LogSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LogSpecification (string name = null, string displayName = null, string blobDuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string blobDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.LogSpecification.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional blobDuration As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.LogSpecification : string * string * string -&gt; Microsoft.Azure.Management.Network.Models.LogSpecification" Usage="new Microsoft.Azure.Management.Network.Models.LogSpecification (name, displayName, blobDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="blobDuration" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="40a2d-103">仕様の名前です。</span><span class="sxs-lookup"><span data-stu-id="40a2d-103">The name of the specification.</span></span></param>
        <param name="displayName"><span data-ttu-id="40a2d-104">仕様の表示名。</span><span class="sxs-lookup"><span data-stu-id="40a2d-104">The display name of the specification.</span></span></param>
        <param name="blobDuration"><span data-ttu-id="40a2d-105">Blob の期間です。</span><span class="sxs-lookup"><span data-stu-id="40a2d-105">Duration of the blob.</span></span></param>
        <summary>
            <span data-ttu-id="40a2d-106">LogSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="40a2d-106">Initializes a new instance of the LogSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobDuration">
      <MemberSignature Language="C#" Value="public string BlobDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LogSpecification.BlobDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobDuration As String" />
      <MemberSignature Language="F#" Value="member this.BlobDuration : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LogSpecification.BlobDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="40a2d-107">取得または blob の期間を設定します。</span><span class="sxs-lookup"><span data-stu-id="40a2d-107">Gets or sets duration of the blob.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LogSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LogSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="40a2d-108">取得または仕様の表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="40a2d-108">Gets or sets the display name of the specification.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LogSpecification.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LogSpecification.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="40a2d-109">取得または仕様の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="40a2d-109">Gets or sets the name of the specification.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>