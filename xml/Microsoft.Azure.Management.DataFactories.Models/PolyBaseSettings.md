<Type Name="PolyBaseSettings" FullName="Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings">
  <TypeSignature Language="C#" Value="public class PolyBaseSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PolyBaseSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class PolyBaseSettings" />
  <TypeSignature Language="F#" Value="type PolyBaseSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7d3c9-101">Polybase の設定です。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-101">Polybase settings.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PolyBaseSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectSampleValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;ulong&gt; RejectSampleValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;unsigned int64&gt; RejectSampleValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectSampleValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectSampleValue As Nullable(Of ULong)" />
      <MemberSignature Language="F#" Value="member this.RejectSampleValue : Nullable&lt;uint64&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectSampleValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.UInt64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d3c9-102">省略可能。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-102">Optional.</span></span> <span data-ttu-id="7d3c9-103">PolyBase が拒否された行の割合を再計算する前に取得しようとする行の数を決定します。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-103">Determines the number of rows to attempt to retrieve before PolyBase recalculates the percentage of rejected rows.</span></span>
            <span data-ttu-id="7d3c9-104">RejectType はときに必要な<see cref="F:Microsoft.Azure.Management.DataFactories.Models.PolyBaseRejectType.Percentage" />します。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-104">Required when RejectType is <see cref="F:Microsoft.Azure.Management.DataFactories.Models.PolyBaseRejectType.Percentage" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectType">
      <MemberSignature Language="C#" Value="public string RejectType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RejectType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectType" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectType As String" />
      <MemberSignature Language="F#" Value="member this.RejectType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d3c9-105">省略可能。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-105">Optional.</span></span> <span data-ttu-id="7d3c9-106">RejectValue がリテラル値またはパーセントとして指定するかどうかを示します。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-106">Indicates whether RejectValue is specified as a literal value or a percentage.</span></span>
            <span data-ttu-id="7d3c9-107">いずれかを指定する必要があります<see cref="T:Microsoft.Azure.Management.DataFactories.Models.PolyBaseRejectType" />です。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-107">Must be one of <see cref="T:Microsoft.Azure.Management.DataFactories.Models.PolyBaseRejectType" />.</span></span>
            <span data-ttu-id="7d3c9-108">既定値は <see cref="F:Microsoft.Azure.Management.DataFactories.Models.PolyBaseRejectType.Value" /> です。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-108">Default value is <see cref="F:Microsoft.Azure.Management.DataFactories.Models.PolyBaseRejectType.Value" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RejectValue">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; RejectValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; RejectValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectValue" />
      <MemberSignature Language="VB.NET" Value="Public Property RejectValue As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.RejectValue : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.RejectValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d3c9-109">省略可能。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-109">Optional.</span></span> <span data-ttu-id="7d3c9-110">または、クエリが失敗する前に拒否されることもの行のパーセンテージの値を指定します。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-110">Specifies the value or the percentage of rows that can be rejected before the query fails.</span></span>
            <span data-ttu-id="7d3c9-111">既定値は 0 です。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-111">Default value is 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseTypeDefault">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseTypeDefault { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseTypeDefault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.UseTypeDefault" />
      <MemberSignature Language="VB.NET" Value="Public Property UseTypeDefault As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseTypeDefault : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.PolyBaseSettings.UseTypeDefault" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d3c9-112">省略可能。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-112">Optional.</span></span> <span data-ttu-id="7d3c9-113">PolyBase がテキスト ファイルからデータを取得する場合にどのように区切りテキスト ファイル内の不足値を処理するかを、指定します。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-113">Specifies how to handle missing values in delimited text files when PolyBase retrieves data from the text file.</span></span>
            <span data-ttu-id="7d3c9-114">既定値は false です。</span><span class="sxs-lookup"><span data-stu-id="7d3c9-114">Default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>