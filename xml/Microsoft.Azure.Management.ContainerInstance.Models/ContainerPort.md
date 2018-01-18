<Type Name="ContainerPort" FullName="Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort">
  <TypeSignature Language="C#" Value="public class ContainerPort" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerPort extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerPort" />
  <TypeSignature Language="F#" Value="type ContainerPort = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="71ae5-101">コンテナーのインスタンスで公開されているポートです。</span><span class="sxs-lookup"><span data-stu-id="71ae5-101">The port exposed on the container instance.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="71ae5-102">ContainerPort クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="71ae5-102">Initializes a new instance of the ContainerPort class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ContainerPort (int port, string protocol = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 port, string protocol) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.#ctor(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (port As Integer, Optional protocol As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort : int * string -&gt; Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort" Usage="new Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort (port, protocol)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="protocol" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="port"><span data-ttu-id="71ae5-103">コンテナー グループ内で公開されているポート番号です。</span><span class="sxs-lookup"><span data-stu-id="71ae5-103">The port number exposed within the container group.</span></span></param>
        <param name="protocol"><span data-ttu-id="71ae5-104">ポートに関連付けられているプロトコルです。</span><span class="sxs-lookup"><span data-stu-id="71ae5-104">The protocol associated with the port.</span></span>
            <span data-ttu-id="71ae5-105">使用可能な値が含まれます: 'TCP'、'UDP'</span><span class="sxs-lookup"><span data-stu-id="71ae5-105">Possible values include: 'TCP', 'UDP'</span></span></param>
        <summary>
            <span data-ttu-id="71ae5-106">ContainerPort クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="71ae5-106">Initializes a new instance of the ContainerPort class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public int Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Integer" />
      <MemberSignature Language="F#" Value="member this.Port : int with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71ae5-107">取得またはコンテナー グループ内で公開されているポート番号を設定します。</span><span class="sxs-lookup"><span data-stu-id="71ae5-107">Gets or sets the port number exposed within the container group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="71ae5-108">取得またはポートに関連付けられているプロトコルを設定します。</span><span class="sxs-lookup"><span data-stu-id="71ae5-108">Gets or sets the protocol associated with the port.</span></span> <span data-ttu-id="71ae5-109">使用可能な値が含まれます: 'TCP'、'UDP'</span><span class="sxs-lookup"><span data-stu-id="71ae5-109">Possible values include: 'TCP', 'UDP'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.Models.ContainerPort.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="containerPort.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="71ae5-110">オブジェクトを検証します。</span><span class="sxs-lookup"><span data-stu-id="71ae5-110">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="71ae5-111">検証が失敗した場合にスローされます。</span><span class="sxs-lookup"><span data-stu-id="71ae5-111">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>