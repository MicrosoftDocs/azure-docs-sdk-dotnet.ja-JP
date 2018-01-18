<Type Name="SiteLimits" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits">
  <TypeSignature Language="C#" Value="public class SiteLimits" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteLimits extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteLimits" />
  <TypeSignature Language="F#" Value="type SiteLimits = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ce27b-101">メトリックは、アプリのセットを制限します。</span><span class="sxs-lookup"><span data-stu-id="ce27b-101">Metric limits set on an app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteLimits ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ce27b-102">SiteLimits クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ce27b-102">Initializes a new instance of the SiteLimits class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteLimits (Nullable&lt;double&gt; maxPercentageCpu = null, Nullable&lt;long&gt; maxMemoryInMb = null, Nullable&lt;long&gt; maxDiskSizeInMb = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;float64&gt; maxPercentageCpu, valuetype System.Nullable`1&lt;int64&gt; maxMemoryInMb, valuetype System.Nullable`1&lt;int64&gt; maxDiskSizeInMb) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits.#ctor(System.Nullable{System.Double},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxPercentageCpu As Nullable(Of Double) = null, Optional maxMemoryInMb As Nullable(Of Long) = null, Optional maxDiskSizeInMb As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits : Nullable&lt;double&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits (maxPercentageCpu, maxMemoryInMb, maxDiskSizeInMb)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxPercentageCpu" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maxMemoryInMb" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="maxDiskSizeInMb" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="maxPercentageCpu"><span data-ttu-id="ce27b-103">最大は、CPU 使用率を使用できます。</span><span class="sxs-lookup"><span data-stu-id="ce27b-103">Maximum allowed CPU usage percentage.</span></span></param>
        <param name="maxMemoryInMb"><span data-ttu-id="ce27b-104">最大は、メモリ使用量を mb 単位で使用できます。</span><span class="sxs-lookup"><span data-stu-id="ce27b-104">Maximum allowed memory usage in MB.</span></span></param>
        <param name="maxDiskSizeInMb"><span data-ttu-id="ce27b-105">許可された最大ディスク サイズの使用率 (MB)。</span><span class="sxs-lookup"><span data-stu-id="ce27b-105">Maximum allowed disk size usage in MB.</span></span></param>
        <summary>
            <span data-ttu-id="ce27b-106">SiteLimits クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="ce27b-106">Initializes a new instance of the SiteLimits class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDiskSizeInMb">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxDiskSizeInMb { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxDiskSizeInMb" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits.MaxDiskSizeInMb" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDiskSizeInMb As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxDiskSizeInMb : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits.MaxDiskSizeInMb" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxDiskSizeInMb")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce27b-107">取得または設定最大ディスク サイズの使用量を mb 単位で許可します。</span><span class="sxs-lookup"><span data-stu-id="ce27b-107">Gets or sets maximum allowed disk size usage in MB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMemoryInMb">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxMemoryInMb { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxMemoryInMb" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits.MaxMemoryInMb" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxMemoryInMb As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxMemoryInMb : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits.MaxMemoryInMb" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxMemoryInMb")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce27b-108">取得または設定最大メモリ使用量を mb 単位で許可します。</span><span class="sxs-lookup"><span data-stu-id="ce27b-108">Gets or sets maximum allowed memory usage in MB.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentageCpu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MaxPercentageCpu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MaxPercentageCpu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits.MaxPercentageCpu" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentageCpu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MaxPercentageCpu : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.SiteLimits.MaxPercentageCpu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxPercentageCpu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ce27b-109">取得または許可された最大の CPU 使用率を設定します。</span><span class="sxs-lookup"><span data-stu-id="ce27b-109">Gets or sets maximum allowed CPU usage percentage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>