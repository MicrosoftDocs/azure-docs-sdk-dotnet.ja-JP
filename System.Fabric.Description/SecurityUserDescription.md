<Type Name="SecurityUserDescription" FullName="System.Fabric.Description.SecurityUserDescription">
  <TypeSignature Language="C#" Value="public sealed class SecurityUserDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SecurityUserDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.SecurityUserDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SecurityUserDescription" />
  <TypeSignature Language="F#" Value="type SecurityUserDescription = class" />
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
      <para>セキュリティ ユーザーの説明を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityUserDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.SecurityUserDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.SecurityUserDescription" /> クラスの新しいインスタンスを初期化します。 </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.SecurityUserDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.Description.SecurityUserDescription.Name" />
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
          <para>アプリケーション マニフェストの環境設定の一部として作成するユーザーの名前を取得します。 </para>
        </summary>
        <value>
          <para>アプリケーション マニフェストの環境設定の一部として作成するユーザーの名前。 </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentApplicationGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ParentApplicationGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ParentApplicationGroups" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.SecurityUserDescription.ParentApplicationGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ParentApplicationGroups As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ParentApplicationGroups : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.Description.SecurityUserDescription.ParentApplicationGroups" />
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
          <para>このユーザーを追加する、セキュリティ グループの説明で、親グループを取得します。 </para>
        </summary>
        <value>
          <para>このユーザーを追加する、セキュリティ グループの説明で親グループ。 </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentSystemGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ParentSystemGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ParentSystemGroups" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.SecurityUserDescription.ParentSystemGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ParentSystemGroups As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ParentSystemGroups : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.Description.SecurityUserDescription.ParentSystemGroups" />
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
          <para>このユーザーを追加するローカル グループを取得します。</para>
        </summary>
        <value>
          <para>このユーザーを追加するローカル グループです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sid">
      <MemberSignature Language="C#" Value="public System.Security.Principal.SecurityIdentifier Sid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Security.Principal.SecurityIdentifier Sid" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.SecurityUserDescription.Sid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sid As SecurityIdentifier" />
      <MemberSignature Language="F#" Value="member this.Sid : System.Security.Principal.SecurityIdentifier" Usage="System.Fabric.Description.SecurityUserDescription.Sid" />
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
            セキュリのプライマリ SecurityIdentifier を取得します。
            </para>
        </summary>
        <value>
              セキュリ プライマリ SecurityIdentifier
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>