<Type Name="Service" FullName="System.Fabric.Query.Service">
  <TypeSignature Language="C#" Value="public abstract class Service" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Service extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Service" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Service" />
  <TypeSignature Language="F#" Value="type Service = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatelessService))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatefulService))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>サービスを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Service.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Service.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>正常性状態を取得します。</para>
        </summary>
        <value>
          <para>正常性状態。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsServiceGroup">
      <MemberSignature Language="C#" Value="public bool IsServiceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsServiceGroup" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Service.IsServiceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsServiceGroup As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsServiceGroup : bool" Usage="System.Fabric.Query.Service.IsServiceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>フラグは、このサービスは、標準のサービスまたはサービス グループかどうかを示します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Boolean" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind ServiceKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind ServiceKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Service.ServiceKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceKind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.ServiceKind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Query.Service.ServiceKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービスの種類を取得します。</para>
        </summary>
        <value>
          <para>サービスの種類。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestVersion">
      <MemberSignature Language="C#" Value="public string ServiceManifestVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Service.ServiceManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestVersion As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestVersion : string" Usage="System.Fabric.Query.Service.ServiceManifestVersion" />
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
          <para>サービス マニフェストのバージョンを取得します。</para>
        </summary>
        <value>
          <para>サービス マニフェスト バージョンです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Service.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Query.Service.ServiceName" />
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
          <para>サービス名を取得します。</para>
        </summary>
        <value>
          <para>サービスの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceStatus ServiceStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceStatus ServiceStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Service.ServiceStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceStatus As ServiceStatus" />
      <MemberSignature Language="F#" Value="member this.ServiceStatus : System.Fabric.Query.ServiceStatus" Usage="System.Fabric.Query.Service.ServiceStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービスの状態を取得します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Query.ServiceStatus" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Service.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Query.Service.ServiceTypeName" />
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
          <para>サービス型の名前を取得します。</para>
        </summary>
        <value>
          <para>サービス型の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>