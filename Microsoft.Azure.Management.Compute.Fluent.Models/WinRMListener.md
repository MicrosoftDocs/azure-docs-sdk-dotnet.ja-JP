<Type Name="WinRMListener" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener">
  <TypeSignature Language="C#" Value="public class WinRMListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WinRMListener extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WinRMListener" />
  <TypeSignature Language="F#" Value="type WinRMListener = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c2690-101">プロトコルと Windows リモート管理のリスナーの拇印について説明します</span><span class="sxs-lookup"><span data-stu-id="c2690-101">Describes Protocol and thumbprint of Windows Remote Management listener</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WinRMListener ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c2690-102">WinRMListener クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c2690-102">Initializes a new instance of the WinRMListener class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WinRMListener (Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; protocol = null, string certificateUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; protocol, string certificateUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.#ctor(System.Nullable{Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional protocol As Nullable(Of ProtocolTypes) = null, Optional certificateUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; * string -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener (protocol, certificateUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt;" />
        <Parameter Name="certificateUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol"><span data-ttu-id="c2690-103">WinRM リスナーで使用されるプロトコルです。</span><span class="sxs-lookup"><span data-stu-id="c2690-103">The Protocol used by the WinRM listener.</span></span>
            <span data-ttu-id="c2690-104">Http と Https がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="c2690-104">Http and Https are supported.</span></span> <span data-ttu-id="c2690-105">使用可能な値が含まれます 'Http'、'Https'。</span><span class="sxs-lookup"><span data-stu-id="c2690-105">Possible values include: 'Http', 'Https'</span></span></param>
        <param name="certificateUrl"><span data-ttu-id="c2690-106">Https リスナーの KMS で証明書の URL。</span><span class="sxs-lookup"><span data-stu-id="c2690-106">The Certificate URL in KMS for Https listeners.</span></span> <span data-ttu-id="c2690-107">Http リスナーを null にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c2690-107">Should be null for Http listeners.</span></span></param>
        <summary>
            <span data-ttu-id="c2690-108">WinRMListener クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="c2690-108">Initializes a new instance of the WinRMListener class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateUrl">
      <MemberSignature Language="C#" Value="public string CertificateUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.CertificateUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateUrl As String" />
      <MemberSignature Language="F#" Value="member this.CertificateUrl : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.CertificateUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2690-109">取得または KMS の Https リスナーを証明書の URL に設定します。</span><span class="sxs-lookup"><span data-stu-id="c2690-109">Gets or sets the Certificate URL in KMS for Https listeners.</span></span> <span data-ttu-id="c2690-110">Http リスナーを null にする必要があります。</span><span class="sxs-lookup"><span data-stu-id="c2690-110">Should be null for Http listeners.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As Nullable(Of ProtocolTypes)" />
      <MemberSignature Language="F#" Value="member this.Protocol : Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.WinRMListener.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Compute.Fluent.Models.ProtocolTypes&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c2690-111">取得または WinRM リスナーで使用されるプロトコルを設定します。</span><span class="sxs-lookup"><span data-stu-id="c2690-111">Gets or sets the Protocol used by the WinRM listener.</span></span> <span data-ttu-id="c2690-112">Http と Https がサポートされます。</span><span class="sxs-lookup"><span data-stu-id="c2690-112">Http and Https are supported.</span></span> <span data-ttu-id="c2690-113">使用可能な値が含まれます 'Http'、'Https'。</span><span class="sxs-lookup"><span data-stu-id="c2690-113">Possible values include: 'Http', 'Https'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>