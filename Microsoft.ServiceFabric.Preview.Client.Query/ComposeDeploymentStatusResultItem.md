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
      <para>特徴は、展開名、アプリケーション名、作成する展開のステータス、およびステータスの詳細を作成する展開状態の結果アイテムを説明します。</para>
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
          <para>URI として、アプリケーションの名前を取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの名前です。</para>
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
          <para>として作成する展開のステータスを取得<see cref="P:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusResultItem.ComposeDeploymentStatus" />です。</para>
        </summary>
        <value>
          <para>作成する展開のステータス。</para>
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
          <para>作成するデプロイの名前を取得します。</para>
        </summary>
        <value>
          <para>作成する展開の名前。</para>
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
          <para>詳細なステータスを取得するエラー メッセージを含む展開を作成します。 </para>
        </summary>
        <value>
          <para>詳細なステータスは、エラー メッセージを含む展開を作成します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>