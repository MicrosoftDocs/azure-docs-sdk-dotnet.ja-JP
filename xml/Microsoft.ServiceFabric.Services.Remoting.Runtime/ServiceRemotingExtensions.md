<Type Name="ServiceRemotingExtensions" FullName="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions">
  <TypeSignature Language="C#" Value="public static class ServiceRemotingExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServiceRemotingExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServiceRemotingExtensions" />
  <TypeSignature Language="F#" Value="type ServiceRemotingExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ce554-101">このクラスを作成する拡張メソッドを追加する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />から派生したサービス インターフェイスのリモート処理メソッドに関する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="ce554-101">This class adds extensions methods to create <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for remoting methods of the service interfaces that are derived from <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateServiceRemotingInstanceListeners&lt;TStatelessService&gt;">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceRemotingInstanceListeners&lt;TStatelessService&gt; (this TStatelessService serviceImplementation) where TStatelessService : Microsoft.ServiceFabric.Services.Runtime.StatelessService, Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; CreateServiceRemotingInstanceListeners&lt;(class Microsoft.ServiceFabric.Services.Runtime.StatelessService, class Microsoft.ServiceFabric.Services.Remoting.IService) TStatelessService&gt;(!!TStatelessService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingInstanceListeners``1(``0)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateServiceRemotingInstanceListeners(Of TStatelessService As {StatelessService, IService}) (serviceImplementation As TStatelessService) As IEnumerable(Of ServiceInstanceListener)" />
      <MemberSignature Language="F#" Value="static member CreateServiceRemotingInstanceListeners : 'StatelessService -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt; (requires 'StatelessService :&gt; Microsoft.ServiceFabric.Services.Runtime.StatelessService and 'StatelessService :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingInstanceListeners serviceImplementation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceInstanceListener&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TStatelessService">
          <Constraints>
            <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatelessService</BaseTypeName>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceImplementation" Type="TStatelessService" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="TStatelessService"><span data-ttu-id="ce554-102">サービス実装の制約を入力します。</span><span class="sxs-lookup"><span data-stu-id="ce554-102">Type constraint on the service implementation.</span></span> <span data-ttu-id="ce554-103">サービスの実装がから派生する必要があります<see cref="T:System.Fabric.Query.StatelessService" />から派生した 1 つまたは複数のインターフェイスを実装および<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="ce554-103">The service implementation must derive from <see cref="T:System.Fabric.Query.StatelessService" /> and implement one or more interfaces that derive from <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</span></span></typeparam>
        <param name="serviceImplementation"><span data-ttu-id="ce554-104">ステートレス サービスの実装。</span><span class="sxs-lookup"><span data-stu-id="ce554-104">A stateless service implementation.</span></span></param>
        <summary>
            <span data-ttu-id="ce554-105">拡張メソッドを作成する、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />ステートレス サービスの実装です。</span><span class="sxs-lookup"><span data-stu-id="ce554-105">An extension method that creates an <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for a stateless service implementation.</span></span>
            </summary>
        <returns><span data-ttu-id="ce554-106">A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />通信リスナーをリモートからの派生インターフェイス<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="ce554-106">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> communication listener that remotes the interfaces deriving from <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener&lt;TStatefulService&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener&lt;TStatefulService&gt; (this TStatefulService serviceImplementation, System.Fabric.StatefulServiceContext serviceContext) where TStatefulService : Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase, Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener&lt;(class Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase, class Microsoft.ServiceFabric.Services.Remoting.IService) TStatefulService&gt;(!!TStatefulService serviceImplementation, class System.Fabric.StatefulServiceContext serviceContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatefulServiceContext)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateServiceRemotingListener(Of TStatefulService As {StatefulServiceBase, IService}) (serviceImplementation As TStatefulService, serviceContext As StatefulServiceContext) As IServiceRemotingListener" />
      <MemberSignature Language="F#" Value="static member CreateServiceRemotingListener : 'StatefulService * System.Fabric.StatefulServiceContext -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener (requires 'StatefulService :&gt; Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase and 'StatefulService :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener (serviceImplementation, serviceContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TStatefulService">
          <Constraints>
            <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase</BaseTypeName>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceImplementation" Type="TStatefulService" RefType="this" />
        <Parameter Name="serviceContext" Type="System.Fabric.StatefulServiceContext" />
      </Parameters>
      <Docs>
        <typeparam name="TStatefulService"><span data-ttu-id="ce554-107">サービス実装の制約を入力します。</span><span class="sxs-lookup"><span data-stu-id="ce554-107">Type constraint on the service implementation.</span></span> <span data-ttu-id="ce554-108">サービスの実装がから派生する必要があります<see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />から派生した 1 つまたは複数のインターフェイスを実装および<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="ce554-108">The service implementation must derive from <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" /> and implement one or more interfaces that derive from <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</span></span></typeparam>
        <param name="serviceImplementation"><span data-ttu-id="ce554-109">ステートフルなサービスの実装。</span><span class="sxs-lookup"><span data-stu-id="ce554-109">A stateful service implementation.</span></span></param>
        <param name="serviceContext"><span data-ttu-id="ce554-110">サービスが動作するコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="ce554-110">The context under which the service is operating.</span></span></param>
        <summary>
            <span data-ttu-id="ce554-111">拡張メソッドを作成する、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />のステートフルなサービスの実装です。</span><span class="sxs-lookup"><span data-stu-id="ce554-111">An extension method that creates an <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for a stateful service implementation.</span></span> <span data-ttu-id="ce554-112">これは、非推奨の実装です。</span><span class="sxs-lookup"><span data-stu-id="ce554-112">This is deprecated implementation.</span></span> <span data-ttu-id="ce554-113">この Api CreateServiceRemotingReplicaListeners を代わりに使用します。</span><span class="sxs-lookup"><span data-stu-id="ce554-113">Use this Api CreateServiceRemotingReplicaListeners instead</span></span>
            </summary>
        <returns><span data-ttu-id="ce554-114">A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />通信リスナーをリモートからの派生インターフェイス<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="ce554-114">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> communication listener that remotes the interfaces deriving from <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingListener&lt;TStatelessService&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener&lt;TStatelessService&gt; (this TStatelessService serviceImplementation, System.Fabric.StatelessServiceContext serviceContext) where TStatelessService : Microsoft.ServiceFabric.Services.Runtime.StatelessService, Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener CreateServiceRemotingListener&lt;(class Microsoft.ServiceFabric.Services.Runtime.StatelessService, class Microsoft.ServiceFabric.Services.Remoting.IService) TStatelessService&gt;(!!TStatelessService serviceImplementation, class System.Fabric.StatelessServiceContext serviceContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener``1(``0,System.Fabric.StatelessServiceContext)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateServiceRemotingListener(Of TStatelessService As {StatelessService, IService}) (serviceImplementation As TStatelessService, serviceContext As StatelessServiceContext) As IServiceRemotingListener" />
      <MemberSignature Language="F#" Value="static member CreateServiceRemotingListener : 'StatelessService * System.Fabric.StatelessServiceContext -&gt; Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener (requires 'StatelessService :&gt; Microsoft.ServiceFabric.Services.Runtime.StatelessService and 'StatelessService :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingListener (serviceImplementation, serviceContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TStatelessService">
          <Constraints>
            <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatelessService</BaseTypeName>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceImplementation" Type="TStatelessService" RefType="this" />
        <Parameter Name="serviceContext" Type="System.Fabric.StatelessServiceContext" />
      </Parameters>
      <Docs>
        <typeparam name="TStatelessService"><span data-ttu-id="ce554-115">サービス実装の制約を入力します。</span><span class="sxs-lookup"><span data-stu-id="ce554-115">Type constraint on the service implementation.</span></span> <span data-ttu-id="ce554-116">サービスの実装がから派生する必要があります<see cref="T:System.Fabric.Query.StatelessService" />から派生した 1 つまたは複数のインターフェイスを実装および<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="ce554-116">The service implementation must derive from <see cref="T:System.Fabric.Query.StatelessService" /> and implement one or more interfaces that derive from <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</span></span></typeparam>
        <param name="serviceImplementation"><span data-ttu-id="ce554-117">ステートレス サービスの実装。</span><span class="sxs-lookup"><span data-stu-id="ce554-117">A stateless service implementation.</span></span></param>
        <param name="serviceContext"><span data-ttu-id="ce554-118">サービスが動作するコンテキスト。</span><span class="sxs-lookup"><span data-stu-id="ce554-118">The context under which the service is operating.</span></span></param>
        <summary>
            <span data-ttu-id="ce554-119">拡張メソッドを作成する、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />ステートレス サービスの実装です。これは、非推奨の実装です。</span><span class="sxs-lookup"><span data-stu-id="ce554-119">An extension method that creates an <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for a stateless service implementation.This is deprecated implementation.</span></span> <span data-ttu-id="ce554-120">CreateServiceRemotingInstanceListeners Api を代わりに使用します。</span><span class="sxs-lookup"><span data-stu-id="ce554-120">Use CreateServiceRemotingInstanceListeners Api instead.</span></span>
            </summary>
        <returns><span data-ttu-id="ce554-121">A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />通信リスナーをリモートからの派生インターフェイス<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="ce554-121">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> communication listener that remotes the interfaces deriving from <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceRemotingReplicaListeners&lt;TStatefulService&gt;">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceRemotingReplicaListeners&lt;TStatefulService&gt; (this TStatefulService serviceImplementation) where TStatefulService : Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase, Microsoft.ServiceFabric.Services.Remoting.IService;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; CreateServiceRemotingReplicaListeners&lt;(class Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase, class Microsoft.ServiceFabric.Services.Remoting.IService) TStatefulService&gt;(!!TStatefulService serviceImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingReplicaListeners``1(``0)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateServiceRemotingReplicaListeners(Of TStatefulService As {StatefulServiceBase, IService}) (serviceImplementation As TStatefulService) As IEnumerable(Of ServiceReplicaListener)" />
      <MemberSignature Language="F#" Value="static member CreateServiceRemotingReplicaListeners : 'StatefulService -&gt; seq&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt; (requires 'StatefulService :&gt; Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase and 'StatefulService :&gt; Microsoft.ServiceFabric.Services.Remoting.IService)" Usage="Microsoft.ServiceFabric.Services.Remoting.Runtime.ServiceRemotingExtensions.CreateServiceRemotingReplicaListeners serviceImplementation" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TStatefulService">
          <Constraints>
            <BaseTypeName>Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase</BaseTypeName>
            <InterfaceName>Microsoft.ServiceFabric.Services.Remoting.IService</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="serviceImplementation" Type="TStatefulService" RefType="this" />
      </Parameters>
      <Docs>
        <typeparam name="TStatefulService">To be added.</typeparam>
        <param name="serviceImplementation"><span data-ttu-id="ce554-122">ステートフルなサービスの実装。</span><span class="sxs-lookup"><span data-stu-id="ce554-122">A stateful service implementation.</span></span></param>
        <summary>
             <span data-ttu-id="ce554-123">拡張メソッドを作成する、<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />のステートフルなサービスの実装です。</span><span class="sxs-lookup"><span data-stu-id="ce554-123">An extension method that creates an <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> for a stateful service implementation.</span></span>
             <span data-ttu-id="ce554-124"><typeparam name="TStatefulService">サービス実装の制約を入力します。サービスの実装がから派生する必要があります<see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" />から派生した 1 つまたは複数のインターフェイスを実装および<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</typeparam></span><span class="sxs-lookup"><span data-stu-id="ce554-124"><typeparam name="TStatefulService">Type constraint on the service implementation. The service implementation must derive from <see cref="T:Microsoft.ServiceFabric.Services.Runtime.StatefulServiceBase" /> and implement one or more interfaces that derive from <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</typeparam></span></span></summary>
        <returns><span data-ttu-id="ce554-125">A<see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" />通信リスナーをリモートからの派生インターフェイス<see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" />インターフェイスです。</span><span class="sxs-lookup"><span data-stu-id="ce554-125">A <see cref="T:Microsoft.ServiceFabric.Services.Remoting.Runtime.IServiceRemotingListener" /> communication listener that remotes the interfaces deriving from <see cref="T:Microsoft.ServiceFabric.Services.Remoting.IService" /> interface.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>