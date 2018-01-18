<Type Name="DeployedApplication" FullName="System.Fabric.Query.DeployedApplication">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplication" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplication extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedApplication" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplication" />
  <TypeSignature Language="F#" Value="type DeployedApplication = class" />
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
      <para><span data-ttu-id="c2074-101">サービス ファブリック ノードで実行されているアプリケーションのサービス ホストのインスタンスについて説明します。</span><span class="sxs-lookup"><span data-stu-id="c2074-101">Describes an instance of an application’s service host running on a Service Fabric Node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Query.DeployedApplication.ApplicationName" />
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
          <para><span data-ttu-id="c2074-102">アプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="c2074-102">Gets the application name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c2074-103">アプリケーション名。</span><span class="sxs-lookup"><span data-stu-id="c2074-103">The application name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Query.DeployedApplication.ApplicationTypeName" />
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
          <para><span data-ttu-id="c2074-104">アプリケーションの種類名を取得します。</span><span class="sxs-lookup"><span data-stu-id="c2074-104">Gets the application type name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c2074-105">アプリケーションの種類名です。</span><span class="sxs-lookup"><span data-stu-id="c2074-105">The application type name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.DeploymentStatus DeployedApplicationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.DeploymentStatus DeployedApplicationStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.DeployedApplicationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationStatus As DeploymentStatus" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationStatus : System.Fabric.DeploymentStatus" Usage="System.Fabric.Query.DeployedApplication.DeployedApplicationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DeploymentStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="c2074-106">展開済みアプリケーション インスタンスの状態を取得します。</span><span class="sxs-lookup"><span data-stu-id="c2074-106">Gets the status of the deployed application instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c2074-107">展開済みアプリケーション インスタンスの状態。</span><span class="sxs-lookup"><span data-stu-id="c2074-107">The status of the deployed application instance.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogDirectory">
      <MemberSignature Language="C#" Value="public string LogDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LogDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.LogDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogDirectory As String" />
      <MemberSignature Language="F#" Value="member this.LogDirectory : string" Usage="System.Fabric.Query.DeployedApplication.LogDirectory" />
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
          <para><span data-ttu-id="c2074-108">展開済みアプリケーション インスタンスによって使用されるログ ディレクトリ パスを取得します。</span><span class="sxs-lookup"><span data-stu-id="c2074-108">Gets the log directory path used by the deployed application instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c2074-109">展開済みアプリケーション インスタンスによって使用されるログ ディレクトリ パス。</span><span class="sxs-lookup"><span data-stu-id="c2074-109">The log directory path used by the deployed application instance.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TempDirectory">
      <MemberSignature Language="C#" Value="public string TempDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TempDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.TempDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TempDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TempDirectory : string" Usage="System.Fabric.Query.DeployedApplication.TempDirectory" />
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
          <para><span data-ttu-id="c2074-110">展開済みアプリケーション インスタンスによって使用される一時ディレクトリのパスを取得します。</span><span class="sxs-lookup"><span data-stu-id="c2074-110">Gets the temp directory path used by the deployed application instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c2074-111">展開済みアプリケーション インスタンスによって使用される一時ディレクトリのパス。</span><span class="sxs-lookup"><span data-stu-id="c2074-111">The temp directory path used by the deployed application instance.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkDirectory">
      <MemberSignature Language="C#" Value="public string WorkDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkDirectory" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedApplication.WorkDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WorkDirectory As String" />
      <MemberSignature Language="F#" Value="member this.WorkDirectory : string" Usage="System.Fabric.Query.DeployedApplication.WorkDirectory" />
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
          <para><span data-ttu-id="c2074-112">展開済みアプリケーションのインスタンスによって使用される作業ディレクトリ パスを取得します。</span><span class="sxs-lookup"><span data-stu-id="c2074-112">Gets the work directory path used by the deployed application instance.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="c2074-113">展開済みアプリケーション インスタンスによって使用される作業ディレクトリのパス。</span><span class="sxs-lookup"><span data-stu-id="c2074-113">The work directory path used by the deployed application instance.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>