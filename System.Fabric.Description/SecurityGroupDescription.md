<Type Name="SecurityGroupDescription" FullName="System.Fabric.Description.SecurityGroupDescription">
  <TypeSignature Language="C#" Value="public sealed class SecurityGroupDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SecurityGroupDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.SecurityGroupDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SecurityGroupDescription" />
  <TypeSignature Language="F#" Value="type SecurityGroupDescription = class" />
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
      <para>セキュリティ グループの説明を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.SecurityGroupDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.SecurityGroupDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainGroupMembers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DomainGroupMembers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DomainGroupMembers" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.SecurityGroupDescription.DomainGroupMembers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainGroupMembers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DomainGroupMembers : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.Description.SecurityGroupDescription.DomainGroupMembers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このグループにメンバーとして追加されるドメイン グループを取得します。</para>
        </summary>
        <value>
          <para>このグループにメンバーとして追加されるドメイン グループです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainUserMembers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DomainUserMembers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DomainUserMembers" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.SecurityGroupDescription.DomainUserMembers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainUserMembers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DomainUserMembers : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.Description.SecurityGroupDescription.DomainUserMembers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このグループにメンバーとして追加するドメイン ユーザーを取得します。</para>
        </summary>
        <value>
          <para>このグループにメンバーとして追加するドメイン ユーザー。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.SecurityGroupDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Description.SecurityGroupDescription.Name" />
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
          <para>アプリケーションの環境のセットアップの一部として作成するグループの名前を取得します。</para>
        </summary>
        <value>
          <para>アプリケーションの環境のセットアップの一部として作成されるグループの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sid">
      <MemberSignature Language="C#" Value="public System.Security.Principal.SecurityIdentifier Sid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.Principal.SecurityIdentifier Sid" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.SecurityGroupDescription.Sid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sid As SecurityIdentifier" />
      <MemberSignature Language="F#" Value="member this.Sid : System.Security.Principal.SecurityIdentifier" Usage="System.Fabric.Description.SecurityGroupDescription.Sid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Principal.SecurityIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            SecurityGroup のプライマリ SecurityIdentifier を取得します。
            </para>
        </summary>
        <value>
             SecurityGroup のプライマリ SecurityIdentifier です。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemGroupMembers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SystemGroupMembers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SystemGroupMembers" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.SecurityGroupDescription.SystemGroupMembers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemGroupMembers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SystemGroupMembers : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.Description.SecurityGroupDescription.SystemGroupMembers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>このグループにメンバーとして追加するシステム グループを取得します。</para>
        </summary>
        <value>
          <para>このグループにメンバーとして追加するシステム グループ。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>