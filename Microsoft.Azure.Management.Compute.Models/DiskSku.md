<Type Name="DiskSku" FullName="Microsoft.Azure.Management.Compute.Models.DiskSku">
  <TypeSignature Language="C#" Value="public class DiskSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiskSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.DiskSku" />
  <TypeSignature Language="VB.NET" Value="Public Class DiskSku" />
  <TypeSignature Language="F#" Value="type DiskSku = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="18c28-101">ディスクとスナップショットの sku 名。</span><span class="sxs-lookup"><span data-stu-id="18c28-101">The disks and snapshots sku name.</span></span> <span data-ttu-id="18c28-102">Standard_LRS または premium_lrs ができます。</span><span class="sxs-lookup"><span data-stu-id="18c28-102">Can be Standard_LRS or Premium_LRS.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiskSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiskSku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="18c28-103">DiskSku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="18c28-103">Initializes a new instance of the DiskSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiskSku (Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; name = null, string tier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; name, string tier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.DiskSku.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Models.StorageAccountTypes},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As Nullable(Of StorageAccountTypes) = null, Optional tier As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.DiskSku : Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; * string -&gt; Microsoft.Azure.Management.Compute.Models.DiskSku" Usage="new Microsoft.Azure.Management.Compute.Models.DiskSku (name, tier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;" />
        <Parameter Name="tier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="18c28-104">Sku の名前です。</span><span class="sxs-lookup"><span data-stu-id="18c28-104">The sku name.</span></span> <span data-ttu-id="18c28-105">使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="18c28-105">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span></param>
        <param name="tier"><span data-ttu-id="18c28-106">Sku の層。</span><span class="sxs-lookup"><span data-stu-id="18c28-106">The sku tier.</span></span></param>
        <summary>
            <span data-ttu-id="18c28-107">DiskSku クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="18c28-107">Initializes a new instance of the DiskSku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.DiskSku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As Nullable(Of StorageAccountTypes)" />
      <MemberSignature Language="F#" Value="member this.Name : Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.DiskSku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.StorageAccountTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18c28-108">取得または sku の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="18c28-108">Gets or sets the sku name.</span></span> <span data-ttu-id="18c28-109">使用可能な値が含まれます: 'Standard_LRS'、'Premium_LRS'</span><span class="sxs-lookup"><span data-stu-id="18c28-109">Possible values include: 'Standard_LRS', 'Premium_LRS'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.DiskSku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string" Usage="Microsoft.Azure.Management.Compute.Models.DiskSku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18c28-110">Sku レベルを取得します。</span><span class="sxs-lookup"><span data-stu-id="18c28-110">Gets the sku tier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>