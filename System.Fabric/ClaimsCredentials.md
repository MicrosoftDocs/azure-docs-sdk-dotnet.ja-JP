<Type Name="ClaimsCredentials" FullName="System.Fabric.ClaimsCredentials">
  <TypeSignature Language="C#" Value="public sealed class ClaimsCredentials : System.Fabric.SecurityCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClaimsCredentials extends System.Fabric.SecurityCredentials" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ClaimsCredentials" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClaimsCredentials&#xA;Inherits SecurityCredentials" />
  <TypeSignature Language="F#" Value="type ClaimsCredentials = class&#xA;    inherit SecurityCredentials" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.SecurityCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>STS (セキュリティ トークン サービス) から取得した要求ベースのセキュリティ資格情報を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClaimsCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ClaimsCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.ClaimsCredentials" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IssuerThumbprints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IssuerThumbprints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.IssuerThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IssuerThumbprints As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IssuerThumbprints : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.ClaimsCredentials.IssuerThumbprints" />
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
          <para>サーバー証明書の発行者の証明書の拇印を取得します。</para>
        </summary>
        <value>
          <para>サーバー証明書の発行者の証明書の拇印。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalClaims">
      <MemberSignature Language="C#" Value="public string LocalClaims { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalClaims" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.LocalClaims" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalClaims As String" />
      <MemberSignature Language="F#" Value="member this.LocalClaims : string with get, set" Usage="System.Fabric.ClaimsCredentials.LocalClaims" />
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
          <para>STS (セキュリティ トークン サービス) から取得した要求トークンの文字列形式を取得します。</para>
        </summary>
        <value>
          <para>STS (セキュリティ トークン サービス) から取得した要求トークンの文字列形式。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.ProtectionLevel ProtectionLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ProtectionLevel ProtectionLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.ProtectionLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionLevel As ProtectionLevel" />
      <MemberSignature Language="F#" Value="member this.ProtectionLevel : System.Fabric.ProtectionLevel with get, set" Usage="System.Fabric.ClaimsCredentials.ProtectionLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ProtectionLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サーバーとの通信の保護レベルを取得します。既定値は<see cref="F:System.Fabric.ProtectionLevel.EncryptAndSign" />します。</para>
        </summary>
        <value>
          <para>サーバーとの通信の保護レベル。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerCommonNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ServerCommonNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ServerCommonNames" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.ServerCommonNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerCommonNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ServerCommonNames : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.ClaimsCredentials.ServerCommonNames" />
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
          <para>サーバー証明書の必要な共通名を取得します。</para>
        </summary>
        <value>
          <para>サーバー証明書の共通名を予期します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ServerThumbprints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ServerThumbprints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ClaimsCredentials.ServerThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerThumbprints As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ServerThumbprints : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.ClaimsCredentials.ServerThumbprints" />
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
            内部使用のみ。
            </summary>
        <value>内部使用のみ。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>