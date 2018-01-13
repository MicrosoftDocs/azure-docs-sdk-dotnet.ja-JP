<Type Name="IPAddressOrRange" FullName="Microsoft.WindowsAzure.Storage.IPAddressOrRange">
  <TypeSignature Language="C#" Value="public class IPAddressOrRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IPAddressOrRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.IPAddressOrRange" />
  <TypeSignature Language="VB.NET" Value="Public Class IPAddressOrRange" />
  <TypeSignature Language="F#" Value="type IPAddressOrRange = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="122f8-101">単一の IP アドレスまたは単一の IP アドレス範囲 (、最小、最大、包括的です。) のいずれかを指定します</span><span class="sxs-lookup"><span data-stu-id="122f8-101">Specifies either a single IP Address or a single range of IP Addresses (a minimum and a maximum, inclusive.)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPAddressOrRange (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IPAddressOrRange.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.IPAddressOrRange : string -&gt; Microsoft.WindowsAzure.Storage.IPAddressOrRange" Usage="new Microsoft.WindowsAzure.Storage.IPAddressOrRange address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address"><span data-ttu-id="122f8-102">IPAddressOrRange オブジェクトを表す IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="122f8-102">The IP Address that the IPAddressOrRange object will represent.</span></span></param>
        <summary>
            <span data-ttu-id="122f8-103">1 つの ip アドレスから IPAddressOrRange クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="122f8-103">Initializes a new instance of the IPAddressOrRange class from a single IPAddress.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPAddressOrRange (string minimum, string maximum);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string minimum, string maximum) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IPAddressOrRange.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minimum As String, maximum As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.IPAddressOrRange : string * string -&gt; Microsoft.WindowsAzure.Storage.IPAddressOrRange" Usage="new Microsoft.WindowsAzure.Storage.IPAddressOrRange (minimum, maximum)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimum" Type="System.String" />
        <Parameter Name="maximum" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="minimum"><span data-ttu-id="122f8-104">IPAddressOrRange オブジェクトは包括的な範囲の境界として使用する最小の IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="122f8-104">The minimum IP Address that the IPAddressOrRange object will use as a range boundary, inclusive.</span></span></param>
        <param name="maximum"><span data-ttu-id="122f8-105">IPAddressOrRange オブジェクトは包括的な範囲の境界として使用する最大 IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="122f8-105">The maximum IP Address that the IPAddressOrRange object will use as a range boundary, inclusive.</span></span></param>
        <summary>
            <span data-ttu-id="122f8-106">2 つの ip アドレスのオブジェクト、最小および最大から IPAddressOrRange クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="122f8-106">Initializes a new instance of the IPAddressOrRange class from two IPAddress objects, a minimum and a maximum.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="122f8-107">IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="122f8-107">The IP Address.</span></span>
            <span data-ttu-id="122f8-108">このオブジェクトは、IP アドレスの範囲を表している場合は null を返します。</span><span class="sxs-lookup"><span data-stu-id="122f8-108">Returns null if this object represents a range of IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSingleAddress">
      <MemberSignature Language="C#" Value="public bool IsSingleAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSingleAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.IsSingleAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSingleAddress As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSingleAddress : bool" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.IsSingleAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="122f8-109">True の場合は、このオブジェクトは、単一の IP アドレス範囲を表す場合は false を表します。</span><span class="sxs-lookup"><span data-stu-id="122f8-109">True if this object represents a single IP Address, false if it represents a range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumAddress">
      <MemberSignature Language="C#" Value="public string MaximumAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaximumAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.MaximumAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumAddress As String" />
      <MemberSignature Language="F#" Value="member this.MaximumAddress : string" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.MaximumAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="122f8-110">包括的に、範囲の最大の IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="122f8-110">The maximum IP Address for the range, inclusive.</span></span>
            <span data-ttu-id="122f8-111">返します。 この場合は、null オブジェクトでは、単一の IP アドレスを表します。</span><span class="sxs-lookup"><span data-stu-id="122f8-111">Returns null if this object represents a single IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinimumAddress">
      <MemberSignature Language="C#" Value="public string MinimumAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MinimumAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.IPAddressOrRange.MinimumAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MinimumAddress As String" />
      <MemberSignature Language="F#" Value="member this.MinimumAddress : string" Usage="Microsoft.WindowsAzure.Storage.IPAddressOrRange.MinimumAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="122f8-112">包括的に、範囲の最小の IP アドレス。</span><span class="sxs-lookup"><span data-stu-id="122f8-112">The minimum IP Address for the range, inclusive.</span></span>
            <span data-ttu-id="122f8-113">返します。 この場合は、null オブジェクトでは、単一の IP アドレスを表します。</span><span class="sxs-lookup"><span data-stu-id="122f8-113">Returns null if this object represents a single IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.IPAddressOrRange.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="iPAddressOrRange.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="122f8-114">この IPAddressOrRange オブジェクトの文字列表現を提供します。</span><span class="sxs-lookup"><span data-stu-id="122f8-114">Provides a string representation of this IPAddressOrRange object.</span></span>
            </summary>
        <returns><span data-ttu-id="122f8-115">この IPAddressOrRange オブジェクトの文字列形式。</span><span class="sxs-lookup"><span data-stu-id="122f8-115">The string representation of this IPAddressOrRange object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>