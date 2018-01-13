<Type Name="ApplicationHealthState" FullName="System.Fabric.Health.ApplicationHealthState">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthState : System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthState extends System.Fabric.Health.EntityHealthState" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthState" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthState&#xA;Inherits EntityHealthState" />
  <TypeSignature Language="F#" Value="type ApplicationHealthState = class&#xA;    inherit EntityHealthState" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.EntityHealthState</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>アプリケーション識別子と、集計された正常性状態を含む、アプリケーションのヘルス状態を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthState.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Health.ApplicationHealthState.ApplicationName" />
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
          <para>アプリケーションの名前を取得します。</para>
        </summary>
        <value>
          <para>アプリケーション名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthState.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthState.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            アプリケーションのヘルス状態について説明する文字列を取得します。
            </summary>
        <returns>アプリケーションの説明の文字列を指定します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>