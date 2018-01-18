<Type Name="ServiceGroupFactory" FullName="System.Fabric.ServiceGroupFactory">
  <TypeSignature Language="C#" Value="public sealed class ServiceGroupFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceGroupFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceGroupFactory" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceGroupFactory" />
  <TypeSignature Language="F#" Value="type ServiceGroupFactory = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="75f20-101">実行時に指定された型ファクトリから実際のサービス グループの作成に使用されるサービス グループ ファクトリを作成します。</span><span class="sxs-lookup"><span data-stu-id="75f20-101">Creates a service group factory that is used to create actual service groups from the provided type factories at runtime.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceGroupFactory ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceGroupFactory.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="75f20-102">空の <see cref="T:System.Fabric.ServiceGroupFactory" /> オブジェクトを作成します。</span><span class="sxs-lookup"><span data-stu-id="75f20-102">Creates an empty <see cref="T:System.Fabric.ServiceGroupFactory" /> object.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddServiceType">
      <MemberSignature Language="C#" Value="public void AddServiceType (string serviceTypeName, Type serviceTypeImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddServiceType(string serviceTypeName, class System.Type serviceTypeImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceGroupFactory.AddServiceType(System.String,System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddServiceType (serviceTypeName As String, serviceTypeImplementation As Type)" />
      <MemberSignature Language="F#" Value="member this.AddServiceType : string * Type -&gt; unit" Usage="serviceGroupFactory.AddServiceType (serviceTypeName, serviceTypeImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceTypeImplementation" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="75f20-103">サービス型名を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="75f20-103">The service type name as a string.</span></span> <span data-ttu-id="75f20-104">マニフェストで指定されているサービスの種類に一致する必要がありますまたは<see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />の<see cref="T:System.Fabric.Description.ServiceGroupDescription" />中に提供される、<see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />呼び出します。</span><span class="sxs-lookup"><span data-stu-id="75f20-104">It should match the service type that is specified in the manifest or the <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> of the <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> that is provided during the <see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" /> call.</span></span></para>
        </param>
        <param name="serviceTypeImplementation">
          <para><span data-ttu-id="75f20-105">完全修飾 (C#) サービスの種類、Service Fabric サービスを実装します。</span><span class="sxs-lookup"><span data-stu-id="75f20-105">The fully qualified C# type of the service that implements the Service Fabric service.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="75f20-106">レジスタ特定のステートフルなまたはステートレス サービス サービス グループ ファクトリのように入力サービス グループのメンバーとして作成できます。</span><span class="sxs-lookup"><span data-stu-id="75f20-106">Registers a particular stateful or stateless service type with the service group factory so that it can be created as a member of the service group.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddStatefulServiceFactory">
      <MemberSignature Language="C#" Value="public void AddStatefulServiceFactory (string serviceTypeName, System.Fabric.IStatefulServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddStatefulServiceFactory(string serviceTypeName, class System.Fabric.IStatefulServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceGroupFactory.AddStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddStatefulServiceFactory (serviceTypeName As String, factory As IStatefulServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.AddStatefulServiceFactory : string * System.Fabric.IStatefulServiceFactory -&gt; unit" Usage="serviceGroupFactory.AddStatefulServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatefulServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="75f20-107">文字列としてのサービス型の名前を示します。</span><span class="sxs-lookup"><span data-stu-id="75f20-107">Indicates the service type name as a string.</span></span> <span data-ttu-id="75f20-108">マニフェストで指定されているサービスの種類に一致する必要がありますまたは<see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />の<see cref="T:System.Fabric.Description.ServiceGroupDescription" />中に提供される、<see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />呼び出します。</span><span class="sxs-lookup"><span data-stu-id="75f20-108">It should match the service type that is specified in the manifest or the <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> of the <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> that is provided during the <see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" /> call.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="75f20-109">追加するステートフルなサービス ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="75f20-109">The stateful service factory to add.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="75f20-110">サービス グループ ファクトリを指定のステートフルなサービス ファクトリを追加します。</span><span class="sxs-lookup"><span data-stu-id="75f20-110">Adds the specified stateful service factory to the service group factory.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddStatelessServiceFactory">
      <MemberSignature Language="C#" Value="public void AddStatelessServiceFactory (string serviceTypeName, System.Fabric.IStatelessServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddStatelessServiceFactory(string serviceTypeName, class System.Fabric.IStatelessServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceGroupFactory.AddStatelessServiceFactory(System.String,System.Fabric.IStatelessServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddStatelessServiceFactory (serviceTypeName As String, factory As IStatelessServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.AddStatelessServiceFactory : string * System.Fabric.IStatelessServiceFactory -&gt; unit" Usage="serviceGroupFactory.AddStatelessServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatelessServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="75f20-111">サービス型名を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="75f20-111">The service type name as a string.</span></span> <span data-ttu-id="75f20-112">マニフェストで指定されているサービスの種類に一致する必要がありますまたは<see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" />の<see cref="T:System.Fabric.Description.ServiceGroupDescription" />中に提供される、<see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />呼び出します。</span><span class="sxs-lookup"><span data-stu-id="75f20-112">It should match the service type that is specified in the manifest or the <see cref="T:System.Fabric.Description.ServiceGroupMemberDescription" /> of the <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> that is provided during the <see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" /> call.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="75f20-113">追加するステートレス サービス ファクトリ。</span><span class="sxs-lookup"><span data-stu-id="75f20-113">The stateless service factory to add.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="75f20-114">サービス グループ ファクトリを指定されたステートレス サービス ファクトリを追加します。</span><span class="sxs-lookup"><span data-stu-id="75f20-114">Adds the specified stateless service factory to the service group factory.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveServiceFactory">
      <MemberSignature Language="C#" Value="public void RemoveServiceFactory (string serviceTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveServiceFactory(string serviceTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ServiceGroupFactory.RemoveServiceFactory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveServiceFactory (serviceTypeName As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveServiceFactory : string -&gt; unit" Usage="serviceGroupFactory.RemoveServiceFactory serviceTypeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="75f20-115">サービス型名を表す文字列。</span><span class="sxs-lookup"><span data-stu-id="75f20-115">The service type name as a string.</span></span> <span data-ttu-id="75f20-116">ファクトリが登録されたときに指定されたサービスの種類と一致している必要があります。</span><span class="sxs-lookup"><span data-stu-id="75f20-116">It should match the service type that was specified when the factory was registered.</span></span> </para>
        </param>
        <summary>
          <para><span data-ttu-id="75f20-117">サービス ファクトリを削除します。</span><span class="sxs-lookup"><span data-stu-id="75f20-117">Removes the service factory.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>