<Type Name="OperationLogSpecification" FullName="Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification">
  <TypeSignature Language="C#" Value="public class OperationLogSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationLogSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationLogSpecification" />
  <TypeSignature Language="F#" Value="type OperationLogSpecification = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fd24e-101">ログに関連する操作についての詳細。</span><span class="sxs-lookup"><span data-stu-id="fd24e-101">Details about an operation related to logs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationLogSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fd24e-102">OperationLogSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fd24e-102">Initializes a new instance of the OperationLogSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationLogSpecification (string name = null, string displayName = null, string blobDuration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string displayName, string blobDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional displayName As String = null, Optional blobDuration As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification : string * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification" Usage="new Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification (name, displayName, blobDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="blobDuration" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="fd24e-103">ログのカテゴリの名前。</span><span class="sxs-lookup"><span data-stu-id="fd24e-103">The name of the log category.</span></span></param>
        <param name="displayName"><span data-ttu-id="fd24e-104">ローカライズされた表示名。</span><span class="sxs-lookup"><span data-stu-id="fd24e-104">Localized display name.</span></span></param>
        <param name="blobDuration"><span data-ttu-id="fd24e-105">顧客のストレージ アカウントの 1 時間あたりに作成される blob です。</span><span class="sxs-lookup"><span data-stu-id="fd24e-105">Blobs created in the customer storage account, per hour.</span></span></param>
        <summary>
            <span data-ttu-id="fd24e-106">OperationLogSpecification クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="fd24e-106">Initializes a new instance of the OperationLogSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobDuration">
      <MemberSignature Language="C#" Value="public string BlobDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobDuration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification.BlobDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobDuration As String" />
      <MemberSignature Language="F#" Value="member this.BlobDuration : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification.BlobDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="fd24e-107">取得または顧客のストレージ アカウントの 1 時間あたりに作成される blob を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd24e-107">Gets or sets blobs created in the customer storage account, per hour.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="fd24e-108">取得またはローカライズされた表示名を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd24e-108">Gets or sets localized display name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            <span data-ttu-id="fd24e-109">取得またはログのカテゴリの名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="fd24e-109">Gets or sets the name of the log category.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>