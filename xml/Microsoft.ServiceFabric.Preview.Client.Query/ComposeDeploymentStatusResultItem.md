<Type Name="ComposeDeploymentStatusResultItem" FullName="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentStatusResultItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentStatusResultItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentStatusResultItem" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentStatusResultItem = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="dce98-101">特徴は、展開名、アプリケーション名、作成する展開のステータス、およびステータスの詳細を作成する展開状態の結果アイテムを説明します。</span><span class="sxs-lookup"><span data-stu-id="dce98-101">Describes a compose deployment status result item which is characterized by deployment name, application name, compose deployment status , and status details.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dce98-102">URI として、アプリケーションの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="dce98-102">Gets the name of the application as a URI.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="dce98-103">アプリケーションの名前です。</span><span class="sxs-lookup"><span data-stu-id="dce98-103">The name of the application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComposeDeploymentStatus">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus ComposeDeploymentStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus ComposeDeploymentStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ComposeDeploymentStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComposeDeploymentStatus As ComposeDeploymentStatus" />
      <MemberSignature Language="F#" Value="member this.ComposeDeploymentStatus : Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ComposeDeploymentStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dce98-104">として作成する展開のステータスを取得<see cref="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ComposeDeploymentStatus" />です。</span><span class="sxs-lookup"><span data-stu-id="dce98-104">Gets the status of the compose deployment as <see cref="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ComposeDeploymentStatus" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="dce98-105">作成する展開のステータス。</span><span class="sxs-lookup"><span data-stu-id="dce98-105">The status of the compose deployment.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentName">
      <MemberSignature Language="C#" Value="public string DeploymentName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.DeploymentName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeploymentName As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentName : string" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.DeploymentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dce98-106">作成するデプロイの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="dce98-106">Gets the name of the compose deployment.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="dce98-107">作成する展開の名前。</span><span class="sxs-lookup"><span data-stu-id="dce98-107">The name of the compose deployment.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Fabric.Common.Serialization.JsonCustomization(IsDefaultValueIgnored=true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="dce98-108">詳細なステータスを取得するエラー メッセージを含む展開を作成します。</span><span class="sxs-lookup"><span data-stu-id="dce98-108">Gets the status details of compose deployment including failure message.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="dce98-109">詳細なステータスは、エラー メッセージを含む展開を作成します。</span><span class="sxs-lookup"><span data-stu-id="dce98-109">The status details of compose deployment including failure message.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>