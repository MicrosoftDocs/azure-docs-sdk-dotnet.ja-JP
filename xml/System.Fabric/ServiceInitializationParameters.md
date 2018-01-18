<Type Name="ServiceInitializationParameters" FullName="System.Fabric.ServiceInitializationParameters">
  <TypeSignature Language="C#" Value="public abstract class ServiceInitializationParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceInitializationParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServiceInitializationParameters" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceInitializationParameters" />
  <TypeSignature Language="F#" Value="type ServiceInitializationParameters = class" />
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
      <para><span data-ttu-id="2974c-101">渡されるサービスの初期化パラメーターの基本クラスを表す、<see cref="M:System.Fabric.IStatefulServiceReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" />サービスのメソッドです。</span><span class="sxs-lookup"><span data-stu-id="2974c-101">Represents the base class for service initialization parameters that are passed to the <see cref="M:System.Fabric.IStatefulServiceReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" /> method of a service.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="2974c-102">派生型では、ステートレスおよびステートフルなサービスに固有の初期化データを定義します。</span><span class="sxs-lookup"><span data-stu-id="2974c-102">Derived types define initialization data that are specific to stateless and stateful services.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="CodePackageActivationContext">
      <MemberSignature Language="C#" Value="public System.Fabric.CodePackageActivationContext CodePackageActivationContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.CodePackageActivationContext CodePackageActivationContext" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceInitializationParameters.CodePackageActivationContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageActivationContext As CodePackageActivationContext" />
      <MemberSignature Language="F#" Value="member this.CodePackageActivationContext : System.Fabric.CodePackageActivationContext" Usage="System.Fabric.ServiceInitializationParameters.CodePackageActivationContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CodePackageActivationContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2974c-103">サービスを含むコード パッケージに関連付けられているアクティブ化コンテキストを指定します。</span><span class="sxs-lookup"><span data-stu-id="2974c-103">Specifies the activation context that is associated with the code package that contains the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2974c-104"><see cref="T:System.Fabric.CodePackageActivationContext" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="2974c-104">Returns <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializationData">
      <MemberSignature Language="C#" Value="public byte[] InitializationData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] InitializationData" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceInitializationParameters.InitializationData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InitializationData As Byte()" />
      <MemberSignature Language="F#" Value="member this.InitializationData : byte[]" Usage="System.Fabric.ServiceInitializationParameters.InitializationData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2974c-105">一部として、サービスの作成者によって提供されるカスタムの初期化データを指定します、<see cref="T:System.Fabric.Description.ServiceDescription" />クラスです。</span><span class="sxs-lookup"><span data-stu-id="2974c-105">Specifies custom initialization data that is provided by the creator of the service as part of the <see cref="T:System.Fabric.Description.ServiceDescription" /> class.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2974c-106"><see cref="T:System.Byte" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="2974c-106">Returns <see cref="T:System.Byte" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceInitializationParameters.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.ServiceInitializationParameters.PartitionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2974c-107">サービス パーティションの一意の識別子を指定します。</span><span class="sxs-lookup"><span data-stu-id="2974c-107">Specifies the unique identifier of the service partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2974c-108"><see cref="T:System.Guid" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="2974c-108">Returns <see cref="T:System.Guid" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceInitializationParameters.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.ServiceInitializationParameters.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2974c-109">サービスのサービス ファブリック名を示します。</span><span class="sxs-lookup"><span data-stu-id="2974c-109">Indicates the Service Fabric name of the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2974c-110"><see cref="T:System.Uri" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="2974c-110">Returns <see cref="T:System.Uri" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServiceInitializationParameters.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.ServiceInitializationParameters.ServiceTypeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="2974c-111">サービスの種類の名前を示します。</span><span class="sxs-lookup"><span data-stu-id="2974c-111">Indicates the name of the type of the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="2974c-112"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="2974c-112">Returns <see cref="T:System.String" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>