<Type Name="RegistryUsage" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage">
  <TypeSignature Language="C#" Value="public class RegistryUsage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegistryUsage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage" />
  <TypeSignature Language="VB.NET" Value="Public Class RegistryUsage" />
  <TypeSignature Language="F#" Value="type RegistryUsage = class" />
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
            <span data-ttu-id="618eb-101">コンテナー レジストリのクォータ使用率。</span><span class="sxs-lookup"><span data-stu-id="618eb-101">The quota usage for a container registry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryUsage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="618eb-102">RegistryUsage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="618eb-102">Initializes a new instance of the RegistryUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistryUsage (string name = null, Nullable&lt;long&gt; limit = null, Nullable&lt;long&gt; currentValue = null, string unit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int64&gt; limit, valuetype System.Nullable`1&lt;int64&gt; currentValue, string unit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage.#ctor(System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional limit As Nullable(Of Long) = null, Optional currentValue As Nullable(Of Long) = null, Optional unit As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage : string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage (name, limit, currentValue, unit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="limit" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="currentValue" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="unit" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="618eb-103">使用法の名前。</span><span class="sxs-lookup"><span data-stu-id="618eb-103">The name of the usage.</span></span></param>
        <param name="limit"><span data-ttu-id="618eb-104">使用率の制限。</span><span class="sxs-lookup"><span data-stu-id="618eb-104">The limit of the usage.</span></span></param>
        <param name="currentValue"><span data-ttu-id="618eb-105">使用率の現在の値。</span><span class="sxs-lookup"><span data-stu-id="618eb-105">The current value of the usage.</span></span></param>
        <param name="unit"><span data-ttu-id="618eb-106">測定単位。</span><span class="sxs-lookup"><span data-stu-id="618eb-106">The unit of measurement.</span></span> <span data-ttu-id="618eb-107">使用可能な値が含まれます: 'Count'、'バイト'</span><span class="sxs-lookup"><span data-stu-id="618eb-107">Possible values include: 'Count', 'Bytes'</span></span></param>
        <summary>
            <span data-ttu-id="618eb-108">RegistryUsage クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="618eb-108">Initializes a new instance of the RegistryUsage class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; CurrentValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; CurrentValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage.CurrentValue" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentValue As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CurrentValue : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage.CurrentValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentValue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="618eb-109">取得または使用率の現在の値を設定します。</span><span class="sxs-lookup"><span data-stu-id="618eb-109">Gets or sets the current value of the usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Limit">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Limit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Limit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage.Limit" />
      <MemberSignature Language="VB.NET" Value="Public Property Limit As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Limit : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage.Limit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="limit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="618eb-110">取得または使用率の制限を設定します。</span><span class="sxs-lookup"><span data-stu-id="618eb-110">Gets or sets the limit of the usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage.Name" />
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
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="618eb-111">取得または使用法の名前を設定します。</span><span class="sxs-lookup"><span data-stu-id="618eb-111">Gets or sets the name of the usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.RegistryUsage.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="618eb-112">取得または測定単位を設定します。</span><span class="sxs-lookup"><span data-stu-id="618eb-112">Gets or sets the unit of measurement.</span></span> <span data-ttu-id="618eb-113">使用可能な値が含まれます: 'Count'、'バイト'</span><span class="sxs-lookup"><span data-stu-id="618eb-113">Possible values include: 'Count', 'Bytes'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>