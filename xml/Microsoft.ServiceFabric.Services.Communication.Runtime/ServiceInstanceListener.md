<Type Name="ServiceInstanceListener" FullName="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener">
  <TypeSignature Language="C#" Value="public sealed class ServiceInstanceListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceInstanceListener extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceInstanceListener" />
  <TypeSignature Language="F#" Value="type ServiceInstanceListener = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e73bc-101">通信リスナーとステートレスなサービス インスタンスのプロパティを表します。</span><span class="sxs-lookup"><span data-stu-id="e73bc-101">Represents the communication listener and its properties for a Stateless Service instance.</span></span>
            <span data-ttu-id="e73bc-102">通信リスナーから与えられたエンドポイントは、通信リスナーの名前に関連付けられます。</span><span class="sxs-lookup"><span data-stu-id="e73bc-102">Endpoints given out by the communication listener are associated with the name of the communication listener.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceInstanceListener (Func&lt;System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; createCommunicationListener, string name = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class System.Fabric.StatelessServiceContext, class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; createCommunicationListener, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.#ctor(System.Func{System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createCommunicationListener As Func(Of StatelessServiceContext, ICommunicationListener), Optional name As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener : Func&lt;System.Fabric.StatelessServiceContext, Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; * string -&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener" Usage="new Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener (createCommunicationListener, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createCommunicationListener" Type="System.Func&lt;System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="createCommunicationListener"><span data-ttu-id="e73bc-103">通信リスナーを作成するためのファクトリ メソッド。</span><span class="sxs-lookup"><span data-stu-id="e73bc-103">Factory method for creating the communication listener.</span></span></param>
        <param name="name"><span data-ttu-id="e73bc-104">通信リスナーの名前です。</span><span class="sxs-lookup"><span data-stu-id="e73bc-104">Name of the communication listener.</span></span> <span data-ttu-id="e73bc-105">このパラメーターは、ステートレスなサービスがある 1 つだけの通信リスナー場合省略可能です。</span><span class="sxs-lookup"><span data-stu-id="e73bc-105">This parameter is optional if the Stateless Service has only one communication listener.</span></span> <span data-ttu-id="e73bc-106">このオプションを指定しない場合は、名前が DefaultName に設定されます。</span><span class="sxs-lookup"><span data-stu-id="e73bc-106">If it is not given, the Name is set to DefaultName.</span></span></param>
        <summary>
            <span data-ttu-id="e73bc-107">ServiceInstanceListener の新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="e73bc-107">Initializes a new instance of ServiceInstanceListener.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCommunicationListener">
      <MemberSignature Language="C#" Value="public Func&lt;System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; CreateCommunicationListener { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class System.Fabric.StatelessServiceContext, class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; CreateCommunicationListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.CreateCommunicationListener" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreateCommunicationListener As Func(Of StatelessServiceContext, ICommunicationListener)" />
      <MemberSignature Language="F#" Value="member this.CreateCommunicationListener : Func&lt;System.Fabric.StatelessServiceContext, Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.CreateCommunicationListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Fabric.StatelessServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e73bc-108">通信リスナーを作成するためのファクトリ メソッドを取得します。</span><span class="sxs-lookup"><span data-stu-id="e73bc-108">Gets the factory method for creating the communication listener.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e73bc-109">通信リスナーを作成するためのファクトリ メソッド。</span><span class="sxs-lookup"><span data-stu-id="e73bc-109">The factory method for creating the communication listener.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="e73bc-110">ファクトリ メソッドがは、<see cref="T:System.Fabric.StatelessServiceContext" />と実装を返します。 通信リスナー<see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />です。</span><span class="sxs-lookup"><span data-stu-id="e73bc-110">The factory method takes in a <see cref="T:System.Fabric.StatelessServiceContext" /> and returns communication listener implementing <see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultName">
      <MemberSignature Language="C#" Value="public const string DefaultName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.DefaultName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultName : string" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.DefaultName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e73bc-111">サービス インスタンスのリスナーの既定の名前。</span><span class="sxs-lookup"><span data-stu-id="e73bc-111">The default name of the Service instance listener.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e73bc-112">サービス インスタンスのリスナーの既定の名前。</span><span class="sxs-lookup"><span data-stu-id="e73bc-112">The default name of the Service instance listener.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="e73bc-113">通信リスナーの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="e73bc-113">Gets the name of the communication listener.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="e73bc-114">通信リスナーの名前。</span><span class="sxs-lookup"><span data-stu-id="e73bc-114">The name of the communication listener.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>