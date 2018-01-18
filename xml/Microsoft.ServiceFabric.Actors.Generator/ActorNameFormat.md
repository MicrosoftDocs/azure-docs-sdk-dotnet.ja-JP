<Type Name="ActorNameFormat" FullName="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat">
  <TypeSignature Language="C#" Value="public static class ActorNameFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ActorNameFormat extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorNameFormat" />
  <TypeSignature Language="F#" Value="type ActorNameFormat = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c8e4b-101">サービス名、アプリケーション名の形式、アクター インターフェイスの型のように名前を生成するための静的メソッドが含まれています。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-101">Contains static methods for generating names like service name, application name form the actor interface type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetActorStateProviderSettingsSectionName">
      <MemberSignature Language="C#" Value="public static string GetActorStateProviderSettingsSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetActorStateProviderSettingsSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetActorStateProviderSettingsSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetActorStateProviderSettingsSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetActorStateProviderSettingsSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetActorStateProviderSettingsSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType">
            <span data-ttu-id="c8e4b-102">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-102">Type of class implementing the actor.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8e4b-103">取得、<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" />アクター サービス用の構成パッケージで指定された構成セクション名。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-103">Gets the <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /> configuration section name specified in configuration package for the actor service.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c8e4b-104">ActorStateProvider 構成セクション名。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-104">ActorStateProvider configuration section name.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="c8e4b-105">ActorStateProvider 構成セクションで指定された値を使用して構成します。<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /></span><span class="sxs-lookup"><span data-stu-id="c8e4b-105">Values specified in ActorStateProvider configuration section are used to configure <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IActorStateProvider" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCodePackageName">
      <MemberSignature Language="C#" Value="public static string GetCodePackageName (Type actorImplementationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetCodePackageName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetCodePackageName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetCodePackageName (Optional actorImplementationType As Type = null) As String" />
      <MemberSignature Language="F#" Value="static member GetCodePackageName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetCodePackageName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-106">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-106">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-107">アクターのサービス パッケージで使用されるコード パッケージ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-107">Gets the code package name used in service package for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-108">コード パッケージの名前。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-108">code package name.</span></span></returns>
        <remarks><span data-ttu-id="c8e4b-109">コード パッケージ名は、サービスとして内からアクセスできます。<see cref="P:System.Fabric.CodePackageActivationContext.CodePackageName" /></span><span class="sxs-lookup"><span data-stu-id="c8e4b-109">Code package name can be accessed from within a service as <see cref="P:System.Fabric.CodePackageActivationContext.CodePackageName" /></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigPackageName">
      <MemberSignature Language="C#" Value="public static string GetConfigPackageName (Type actorImplementationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetConfigPackageName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetConfigPackageName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetConfigPackageName (Optional actorImplementationType As Type = null) As String" />
      <MemberSignature Language="F#" Value="static member GetConfigPackageName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetConfigPackageName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-110">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-110">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-111">アクター サービス パッケージで使用される構成パッケージ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-111">Gets the configuration package name used in service package for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-112">構成パッケージの名前です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-112">configuration package name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricApplicationName">
      <MemberSignature Language="C#" Value="public static string GetFabricApplicationName (string appPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricApplicationName(string appPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricApplicationName (appPrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricApplicationName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationName appPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appPrefix"><span data-ttu-id="c8e4b-113">アプリケーション名に使用するプレフィックスです。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-113">Prefix to be used for the application name.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-114">Service Fabric クラスター内のアプリケーションの作成に使用するアプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-114">Gets the application name used to create application in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-115">アプリケーションの名前。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-115">Application name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricApplicationPackageName">
      <MemberSignature Language="C#" Value="public static string GetFabricApplicationPackageName (string appPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricApplicationPackageName(string appPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationPackageName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricApplicationPackageName (appPrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricApplicationPackageName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationPackageName appPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appPrefix"><span data-ttu-id="c8e4b-116">アプリケーション パッケージ名に使用するプレフィックスです。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-116">Prefix to be used for the application package name.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-117">アクターの Service Fabric アプリケーションのパッケージを作成するために使用するパッケージ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-117">Gets package name used to create Service Fabric Application package for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-118">アプリケーション パッケージの名前です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-118">Application package name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricApplicationTypeName">
      <MemberSignature Language="C#" Value="public static string GetFabricApplicationTypeName (string appPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricApplicationTypeName(string appPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationTypeName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricApplicationTypeName (appPrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricApplicationTypeName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricApplicationTypeName appPrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appPrefix"><span data-ttu-id="c8e4b-119">アプリケーションの種類名に使用するプレフィックスです。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-119">Prefix to be used for the application type name.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-120">アクターの Service Fabric アプリケーションのパッケージを作成するときに、アプリケーション マニフェストで使用されるアプリケーションの種類名を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-120">Gets the application type name used in application manifest when creating Service Fabric Application package for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-121">アプリケーションの種類の名前です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-121">Application type name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceEndpointName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceEndpointName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceEndpointName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceEndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceEndpointName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceEndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceEndpointName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-122">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-122">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-123">アクター サービスのサービス マニフェストに指定されているアクターの種類のサービス エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-123">Gets the service endpoint for the actor type which is specified in service manifest for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-124">サービス エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-124">Service endpoint name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceName (Type actorInterfaceType, string serviceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceName(class System.Type actorInterfaceType, string serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName(System.Type,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceName (actorInterfaceType As Type, Optional serviceName As String = null) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceName : Type * string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceName (actorInterfaceType, serviceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="serviceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="c8e4b-125">アクター インターフェイスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-125">Type of the actor interface.</span></span></param>
        <param name="serviceName"><span data-ttu-id="c8e4b-126">アクターの種類をホストするサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-126">Name of service hosting the actor type.</span></span> <span data-ttu-id="c8e4b-127">この値が null の場合サービス名は、使用して、actorInterfaceType で作成されます。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-127">If this value is null then service name is constructed using the actorInterfaceType.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-128">Service Fabric クラスター内のアクターの種類をホストするサービスの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-128">Gets name of service which hosts the actor type in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-129">Service Fabric サービスの名前はアクターの種類をホストしています。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-129">Service Fabric service name hosting the actor type.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServicePackageName">
      <MemberSignature Language="C#" Value="public static string GetFabricServicePackageName (string servicePackageNamePrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServicePackageName(string servicePackageNamePrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServicePackageName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServicePackageName (servicePackageNamePrefix As String) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServicePackageName : string -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServicePackageName servicePackageNamePrefix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="servicePackageNamePrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="servicePackageNamePrefix"><span data-ttu-id="c8e4b-130">サービス パッケージ名に使用するプレフィックスです。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-130">Prefix to be used for the service package name.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-131">アクターの Service Fabric アプリケーションのパッケージで使用されているサービス パッケージ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-131">Gets service package name which is used in Service Fabric Application package for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-132">サービス パッケージ名です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-132">Service package name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorConfigSectionName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorConfigSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorConfigSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorConfigSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorConfigSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorConfigSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorConfigSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-133">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-133">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-134">取得レプリケーター構成セクションのアクター サービス用の構成パッケージで指定された名前。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-134">Gets the replicator configuration section name specified in configuration package for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-135">レプリケーター構成セクション名。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-135">Replicator configuration section name.</span></span></returns>
        <remarks><span data-ttu-id="c8e4b-136">レプリケーターの構成 セクションで指定された値を使用して構成<see cref="T:System.Fabric.ReplicatorSettings" />アクターの状態のプライマリ レプリカとセカンダリ レプリカの間でレプリケーション用です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-136">Values specified in replicator configuration section are used to configure <see cref="T:System.Fabric.ReplicatorSettings" /> for the replication of actor state between primary and secondary replicas.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorEndpointName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorEndpointName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorEndpointName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorEndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorEndpointName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorEndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorEndpointName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-137">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-137">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-138">アクター サービスのサービス マニフェストに指定されているレプリケーター エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-138">Gets the replicator endpoint which is specified in service manifest for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-139">サービスのレプリケーター エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-139">Service replicator endpoint name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorSecurityConfigSectionName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorSecurityConfigSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorSecurityConfigSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityConfigSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorSecurityConfigSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorSecurityConfigSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityConfigSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-140">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-140">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-141">レプリケーター セキュリティの構成セクション アクター サービス用の構成パッケージで指定された名前を取得。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-141">Gets the replicator security configuration section name specified in configuration package for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-142">レプリケーターのセキュリティの構成セクション名。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-142">Replicator security configuration section name.</span></span></returns>
        <remarks><span data-ttu-id="c8e4b-143">レプリケーターのセキュリティ構成 セクションで指定された値を使用して構成<see cref="P:System.Fabric.ReplicatorSettings.SecurityCredentials" />アクターの状態のプライマリ レプリカとセカンダリ レプリカの間でレプリケーション用です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-143">Values specified in replicator security configuration section are used to configure <see cref="P:System.Fabric.ReplicatorSettings.SecurityCredentials" /> for the replication of actor state between primary and secondary replicas.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceReplicatorSecurityCredentialTypeName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceReplicatorSecurityCredentialTypeName (Type actorImplementationType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceReplicatorSecurityCredentialTypeName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityCredentialTypeName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceReplicatorSecurityCredentialTypeName (Optional actorImplementationType As Type = null) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceReplicatorSecurityCredentialTypeName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceReplicatorSecurityCredentialTypeName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-144">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-144">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-145">アクター サービスの構成パッケージで複製物作成会社のセキュリティ構成 セクションで使用される資格情報の型名を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-145">Gets the credential type name used in replicator security configuration section in configuration package for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-146">レプリケーター セキュリティ資格情報の種類の名前。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-146">Replicator security credential type name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceTransportSettingsSectionName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceTransportSettingsSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceTransportSettingsSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTransportSettingsSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceTransportSettingsSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceTransportSettingsSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTransportSettingsSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-147">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-147">Type of class implementing the actor.</span></span></param>
        <summary>
             <span data-ttu-id="c8e4b-148">アクター サービス用の構成パッケージで指定された fabrictransport 構成セクション名を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-148">Gets the fabrictransport configuration section name specified in configuration package for the actor service.</span></span>
             </summary>
        <returns><span data-ttu-id="c8e4b-149">FabricTransport 構成セクション名。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-149">FabricTransport configuration section name.</span></span></returns>
        <remarks><span data-ttu-id="c8e4b-150">FabricTransport 構成セクションで指定された値を使用して構成する<see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" />通信します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-150">Values specified in FabricTransport configuration section are used to configure <see cref="T:Microsoft.ServiceFabric.Services.Remoting.FabricTransport.Runtime.FabricTransportRemotingListenerSettings" /> for the communication.</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceTypeName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceTypeName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceTypeName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTypeName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceTypeName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceTypeName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceTypeName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-151">アクターの実装の型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-151">Actor implementation type.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-152">アクターのサービス型の名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-152">Gets service type name for the actor.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-153">サービス型の名前。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-153">Service type name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri actorInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="c8e4b-154">アクター インターフェイスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-154">Type of the actor interface.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-155">サービスの Service Fabric クラスター内のアクターの種類をホストする Uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-155">Gets service Uri which hosts the actor type in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-156">Service Fabric サービスのアクターの種類をホストしている Uri。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-156">Service Fabric service Uri hosting the actor type.</span></span></returns>
        <remarks><span data-ttu-id="c8e4b-157">メソッドからのアプリケーション名を取得しようとします。<see cref="T:System.Fabric.CodePackageActivationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-157">Method will try to get application name from <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span>
            <span data-ttu-id="c8e4b-158">メソッドはまだアプリケーション名を判別できない場合<see cref="T:System.ArgumentException" />がスローされます。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-158">If the method still cannot determine application name, <see cref="T:System.ArgumentException" /> is thrown.</span></span> </remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="c8e4b-159">使用してアプリケーションの名前を特定できない場合<see cref="T:System.Fabric.CodePackageActivationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-159">When application name cannot be determined using <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType, Uri applicationUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType, class System.Uri applicationUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type, applicationUri As Uri) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type * Uri -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri (actorInterfaceType, applicationUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="applicationUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="c8e4b-160">アクター インターフェイスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-160">Type of the actor interface.</span></span></param>
        <param name="applicationUri"><span data-ttu-id="c8e4b-161">Service Fabric アプリケーション アクター サービスを含む Uri です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-161">Service Fabric application Uri containing the actor service.</span></span>
            <span data-ttu-id="c8e4b-162">アプリケーション名がから取得した場合、この値は null<see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-162">If this value is null application name is obtained from <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-163">サービスの Service Fabric クラスター内のアクターの種類をホストする Uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-163">Gets service Uri which hosts the actor type in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-164">Service Fabric サービスのアクターの種類をホストしている Uri。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-164">Service Fabric service Uri hosting the actor type.</span></span></returns>
        <remarks><span data-ttu-id="c8e4b-165">メソッドは、actorInterfaceType を使用してサービス名を作成します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-165">Method will create service name using the actorInterfaceType.</span></span> <span data-ttu-id="c8e4b-166">アプリケーション名を取得しようとは applicationUri が null として渡されると場合、<see cref="T:System.Fabric.CodePackageActivationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-166">If applicationUri is passed as null, an attempt is made to get application name from <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span> <span data-ttu-id="c8e4b-167">メソッドはまだアプリケーション名を判別できない場合<see cref="T:System.ArgumentException" />がスローされます。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-167">If the method still cannot determine application name, <see cref="T:System.ArgumentException" /> is thrown.</span></span> </remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="c8e4b-168">使用してアプリケーションの名前を特定できない場合<see cref="T:System.Fabric.CodePackageActivationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-168">When application name cannot be determined using <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType, string applicationName = null, string serviceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType, string applicationName, string serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type, Optional applicationName As String = null, Optional serviceName As String = null) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type * string * string -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri (actorInterfaceType, applicationName, serviceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="serviceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="c8e4b-169">アクター インターフェイスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-169">Type of the actor interface.</span></span></param>
        <param name="applicationName"><span data-ttu-id="c8e4b-170">Service Fabric アプリケーションの名前を含む、アクター サービス。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-170">Service Fabric application name containing the actor service.</span></span>
            <span data-ttu-id="c8e4b-171">アプリケーション名がから取得した場合、この値は null<see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-171">If this value is null application name is obtained from <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />.</span></span></param>
        <param name="serviceName"><span data-ttu-id="c8e4b-172">アクターの種類をホストするサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-172">Name of service hosting the actor type.</span></span> <span data-ttu-id="c8e4b-173">この値が null の場合サービス名は、使用して、actorInterfaceType で作成されます。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-173">If this value is null then service name is constructed using the actorInterfaceType.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-174">サービスの Service Fabric クラスター内のアクターの種類をホストする Uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-174">Gets service Uri which hosts the actor type in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-175">Service Fabric サービスのアクターの種類をホストしている Uri。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-175">Service Fabric service Uri hosting the actor type.</span></span></returns>
        <remarks><span data-ttu-id="c8e4b-176">アプリケーション名を取得しようとは、applicationName が null または空の文字列として渡されると場合、<see cref="T:System.Fabric.CodePackageActivationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-176">If applicationName is passed as null or empty string, an attempt is made to get application name from <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span> <span data-ttu-id="c8e4b-177">メソッドはまだアプリケーション名を判別できない場合<see cref="T:System.ArgumentException" />がスローされます。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-177">If the method still cannot determine application name, <see cref="T:System.ArgumentException" /> is thrown.</span></span> </remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="c8e4b-178">使用して applicationName を特定できない場合<see cref="T:System.Fabric.CodePackageActivationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-178">When applicationName cannot be determined using <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceUri">
      <MemberSignature Language="C#" Value="public static Uri GetFabricServiceUri (Type actorInterfaceType, Uri applicationUri, string serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri GetFabricServiceUri(class System.Type actorInterfaceType, class System.Uri applicationUri, string serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri(System.Type,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceUri (actorInterfaceType As Type, applicationUri As Uri, serviceName As String) As Uri" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceUri : Type * Uri * string -&gt; Uri" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceUri (actorInterfaceType, applicationUri, serviceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
        <Parameter Name="applicationUri" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="c8e4b-179">アクター インターフェイスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-179">Type of the actor interface.</span></span></param>
        <param name="applicationUri"><span data-ttu-id="c8e4b-180">Service Fabric アプリケーション アクター サービスを含む Uri です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-180">Service Fabric application Uri containing the actor service.</span></span>
            <span data-ttu-id="c8e4b-181">アプリケーション名がから取得した場合、この値は null<see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-181">If this value is null application name is obtained from <see cref="P:System.Fabric.CodePackageActivationContext.ApplicationName" />.</span></span></param>
        <param name="serviceName"><span data-ttu-id="c8e4b-182">アクターの種類をホストするサービスの名前です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-182">Name of service hosting the actor type.</span></span> <span data-ttu-id="c8e4b-183">この値が null の場合サービス名は、使用して、actorInterfaceType で作成されます。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-183">If this value is null then service name is constructed using the actorInterfaceType.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-184">サービスの Service Fabric クラスター内のアクターの種類をホストする Uri を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-184">Gets service Uri which hosts the actor type in Service Fabric cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-185">Service Fabric サービスのアクターの種類をホストしている Uri。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-185">Service Fabric service Uri hosting the actor type.</span></span></returns>
        <remarks><span data-ttu-id="c8e4b-186">アプリケーション名を取得しようとは applicationUri が null として渡されると場合、<see cref="T:System.Fabric.CodePackageActivationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-186">If applicationUri is passed as null, an attempt is made to get application name from <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span> <span data-ttu-id="c8e4b-187">メソッドはまだアプリケーション名を判別できない場合<see cref="T:System.ArgumentException" />がスローされます。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-187">If the method still cannot determine application name, <see cref="T:System.ArgumentException" /> is thrown.</span></span> </remarks>
        <exception cref="T:System.ArgumentException">
            <span data-ttu-id="c8e4b-188">使用してアプリケーションの名前を特定できない場合<see cref="T:System.Fabric.CodePackageActivationContext" />です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-188">When application name cannot be determined using <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricServiceV2EndpointName">
      <MemberSignature Language="C#" Value="public static string GetFabricServiceV2EndpointName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetFabricServiceV2EndpointName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceV2EndpointName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetFabricServiceV2EndpointName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetFabricServiceV2EndpointName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetFabricServiceV2EndpointName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-189">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-189">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-190">アクター サービスのサービス マニフェストに指定されているアクターの種類のサービス エンドポイントを取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-190">Gets the service endpoint for the actor type which is specified in service manifest for the actor service.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-191">サービス エンドポイントの名前。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-191">Service endpoint name.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLocalEseStoreConfigSectionName">
      <MemberSignature Language="C#" Value="public static string GetLocalEseStoreConfigSectionName (Type actorImplementationType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetLocalEseStoreConfigSectionName(class System.Type actorImplementationType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetLocalEseStoreConfigSectionName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetLocalEseStoreConfigSectionName (actorImplementationType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetLocalEseStoreConfigSectionName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetLocalEseStoreConfigSectionName actorImplementationType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorImplementationType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorImplementationType"><span data-ttu-id="c8e4b-192">アクターを実装するクラスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-192">Type of class implementing the actor.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-193">アクター サービス用の構成パッケージで指定されたローカル ストアの構成セクション名を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-193">Gets local store configuration section name specified in configuration package for the actor service.</span></span> 
            </summary>
        <returns><span data-ttu-id="c8e4b-194">ローカル ストアの構成セクション名。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-194">Local store configuration section name.</span></span></returns>
        <remarks><span data-ttu-id="c8e4b-195">ローカルの ESE 構成セクションで指定された値を使用して構成<see cref="T:System.Fabric.LocalEseStoreSettings" />アクターの状態を格納するためです。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-195">Values specified in local ESE configuration section are used to configure <see cref="T:System.Fabric.LocalEseStoreSettings" /> for storing the state of actor.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetName">
      <MemberSignature Language="C#" Value="public static string GetName (Type actorInterfaceType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetName(class System.Type actorInterfaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetName(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetName (actorInterfaceType As Type) As String" />
      <MemberSignature Language="F#" Value="static member GetName : Type -&gt; string" Usage="Microsoft.ServiceFabric.Actors.Generator.ActorNameFormat.GetName actorInterfaceType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="actorInterfaceType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="actorInterfaceType"><span data-ttu-id="c8e4b-196">アクター インターフェイスの型。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-196">Type of the actor interface.</span></span></param>
        <summary>
            <span data-ttu-id="c8e4b-197">ActorInterfaceType からアクターの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-197">Gets name of Actor from actorInterfaceType.</span></span>
            </summary>
        <returns><span data-ttu-id="c8e4b-198">アクターの名前です。</span><span class="sxs-lookup"><span data-stu-id="c8e4b-198">Name of Actor.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>