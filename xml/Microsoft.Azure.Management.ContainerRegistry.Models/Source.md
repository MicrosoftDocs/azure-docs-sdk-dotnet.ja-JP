<Type Name="Source" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Source">
  <TypeSignature Language="C#" Value="public class Source" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Source extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Source" />
  <TypeSignature Language="VB.NET" Value="Public Class Source" />
  <TypeSignature Language="F#" Value="type Source = class" />
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
            <span data-ttu-id="0eb0e-101">イベントを生成したレジストリ ノードです。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-101">The registry node that generated the event.</span></span> <span data-ttu-id="0eb0e-102">ソースはアクターは、イベントが開始中には、put が異なりを生成します。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-102">Put differently, while the actor initiates the event, the source generates it.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Source ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Source.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0eb0e-103">ソース クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-103">Initializes a new instance of the Source class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Source (string addr = null, string instanceID = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string addr, string instanceID) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Source.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional addr As String = null, Optional instanceID As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Source : string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Source" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Source (addr, instanceID)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addr" Type="System.String" />
        <Parameter Name="instanceID" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="addr"><span data-ttu-id="0eb0e-104">IP またはホスト名と、イベントを生成したレジストリ ノードのポートです。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-104">The IP or hostname and the port of the registry node that generated the event.</span></span> <span data-ttu-id="0eb0e-105">一般に、この os で解決されます。実行中のポートと共に Hostname() です。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-105">Generally, this will be resolved by os.Hostname() along with the running port.</span></span></param>
        <param name="instanceID"><span data-ttu-id="0eb0e-106">アプリケーションの実行中のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-106">The running instance of an application.</span></span>
            <span data-ttu-id="0eb0e-107">各再起動後に変更します。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-107">Changes after each restart.</span></span></param>
        <summary>
            <span data-ttu-id="0eb0e-108">ソース クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-108">Initializes a new instance of the Source class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Addr">
      <MemberSignature Language="C#" Value="public string Addr { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Addr" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Source.Addr" />
      <MemberSignature Language="VB.NET" Value="Public Property Addr As String" />
      <MemberSignature Language="F#" Value="member this.Addr : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Source.Addr" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="addr")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0eb0e-109">取得または ip アドレスまたはホスト名と、イベントを生成したレジストリ ノードのポートを設定します。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-109">Gets or sets the IP or hostname and the port of the registry node that generated the event.</span></span> <span data-ttu-id="0eb0e-110">一般に、この os で解決されます。実行中のポートと共に Hostname() です。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-110">Generally, this will be resolved by os.Hostname() along with the running port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceID">
      <MemberSignature Language="C#" Value="public string InstanceID { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceID" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Source.InstanceID" />
      <MemberSignature Language="VB.NET" Value="Public Property InstanceID As String" />
      <MemberSignature Language="F#" Value="member this.InstanceID : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Source.InstanceID" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="instanceID")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0eb0e-111">取得またはアプリケーションの実行中のインスタンスを設定します。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-111">Gets or sets the running instance of an application.</span></span> <span data-ttu-id="0eb0e-112">各再起動後に変更します。</span><span class="sxs-lookup"><span data-stu-id="0eb0e-112">Changes after each restart.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>