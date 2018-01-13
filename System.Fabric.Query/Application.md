<Type Name="Application" FullName="System.Fabric.Query.Application">
  <TypeSignature Language="C#" Value="public sealed class Application" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Application extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Application" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Application" />
  <TypeSignature Language="F#" Value="type Application = class" />
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
      <para>アプリケーション インスタンスの特徴は、アプリケーション名、アプリケーションの種類、アプリケーション パラメーターなどのヘルス状態を説明します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationDefinitionKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationDefinitionKind ApplicationDefinitionKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationDefinitionKind ApplicationDefinitionKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationDefinitionKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationDefinitionKind As ApplicationDefinitionKind" />
      <MemberSignature Language="F#" Value="member this.ApplicationDefinitionKind : System.Fabric.Query.ApplicationDefinitionKind" Usage="System.Fabric.Query.Application.ApplicationDefinitionKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationDefinitionKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>定義の種類を取得します。</para>
        </summary>
        <value>
          <para>定義の種類の列挙で定義されている値の 1 つを含む<see cref="P:System.Fabric.Query.Application.ApplicationDefinitionKind" />です。</para>
          <para>Service Fabric アプリケーションの定義に使用するユーザーのメカニズムを指定します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Query.Application.ApplicationName" />
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
          <para>URI として、アプリケーションの名前を取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの名前です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationParameterList ApplicationParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationParameterList ApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationParameters As ApplicationParameterList" />
      <MemberSignature Language="F#" Value="member this.ApplicationParameters : System.Fabric.Description.ApplicationParameterList" Usage="System.Fabric.Query.Application.ApplicationParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationParameterList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>キーと対応する値のコレクションでは、アプリケーションのパラメーターを取得します。</para>
        </summary>
        <value>
          <para>アプリケーションのパラメーターです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ApplicationStatus ApplicationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ApplicationStatus ApplicationStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationStatus As ApplicationStatus" />
      <MemberSignature Language="F#" Value="member this.ApplicationStatus : System.Fabric.Query.ApplicationStatus" Usage="System.Fabric.Query.Application.ApplicationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ApplicationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>アプリケーションの状態を取得<see cref="T:System.Fabric.Query.ApplicationStatus" />です。</para>
        </summary>
        <value>
          <para>アプリケーションの状態です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.Query.Application.ApplicationTypeName" />
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
          <para>アプリケーション マニフェストで指定されているアプリケーションの種類の名前を取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの種類名です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string ApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.ApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeVersion : string" Usage="System.Fabric.Query.Application.ApplicationTypeVersion" />
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
          <para>アプリケーション マニフェストで指定されているアプリケーションの種類のバージョンを取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの種類のバージョン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Application.HealthState" />
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
          <para>アプリケーションの集計された正常性状態を取得<see cref="T:System.Fabric.Health.HealthState" />です。 </para>
        </summary>
        <value>
          <para>アプリケーションの集計された正常性。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeParameters">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationParameterList UpgradeParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationParameterList UpgradeParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.UpgradeParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeParameters As ApplicationParameterList" />
      <MemberSignature Language="F#" Value="member this.UpgradeParameters : System.Fabric.Description.ApplicationParameterList" Usage="System.Fabric.Query.Application.UpgradeParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use ApplicationUpgradeProgress.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationParameterList</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>非推奨: は使用しないでください。 参照してください<see cref="T:System.Fabric.ApplicationUpgradeProgress" />代わりにします。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.Description.ApplicationParameterList" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTypeVersion">
      <MemberSignature Language="C#" Value="public string UpgradeTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Application.UpgradeTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeTypeVersion : string" Usage="System.Fabric.Query.Application.UpgradeTypeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use ApplicationUpgradeProgress.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>非推奨: は使用しないでください。 参照してください<see cref="T:System.Fabric.ApplicationUpgradeProgress" />代わりにします。</para>
        </summary>
        <value>
          <para><see cref="T:System.String" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>