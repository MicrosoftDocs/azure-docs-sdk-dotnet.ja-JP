<Type Name="StatefulService" FullName="System.Fabric.Query.StatefulService">
  <TypeSignature Language="C#" Value="public sealed class StatefulService : System.Fabric.Query.Service" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulService extends System.Fabric.Query.Service" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.StatefulService" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulService&#xA;Inherits Service" />
  <TypeSignature Language="F#" Value="type StatefulService = class&#xA;    inherit Service" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.Service</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>ステートフルなサービスを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HasPersistedState">
      <MemberSignature Language="C#" Value="public bool HasPersistedState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasPersistedState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.StatefulService.HasPersistedState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasPersistedState As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasPersistedState : bool" Usage="System.Fabric.Query.StatefulService.HasPersistedState" />
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
          <para>現在のサービスの状態が永続化するかどうかを決定する値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>状態です。 それ以外の場合、現在のサービスが永続化場合<languageKeyword>false</languageKeyword>です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>