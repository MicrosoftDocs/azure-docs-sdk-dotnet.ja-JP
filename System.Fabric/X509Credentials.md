<Type Name="X509Credentials" FullName="System.Fabric.X509Credentials">
  <TypeSignature Language="C#" Value="public sealed class X509Credentials : System.Fabric.SecurityCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit X509Credentials extends System.Fabric.SecurityCredentials" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.X509Credentials" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class X509Credentials&#xA;Inherits SecurityCredentials" />
  <TypeSignature Language="F#" Value="type X509Credentials = class&#xA;    inherit SecurityCredentials" />
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
      <para>X.509 証明書に基づくセキュリティ資格情報を指定します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public X509Credentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.X509Credentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
          <see cref="T:System.Fabric.X509Credentials" /> クラスの新しいインスタンスを作成します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedCommonNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedCommonNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedCommonNames" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.AllowedCommonNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllowedCommonNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedCommonNames : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.X509Credentials.AllowedCommonNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated by RemoteCommonNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>RemoteCommonNames で推奨されなくなりました。</para>
        </summary>
        <value>
          <para>検証に使用する Service Fabric を使用できる一般的な名前です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindType">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.X509Certificates.X509FindType FindType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Security.Cryptography.X509Certificates.X509FindType FindType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.FindType" />
      <MemberSignature Language="VB.NET" Value="Public Property FindType As X509FindType" />
      <MemberSignature Language="F#" Value="member this.FindType : System.Security.Cryptography.X509Certificates.X509FindType with get, set" Usage="System.Fabric.X509Credentials.FindType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.X509FindType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para> ローカルの証明書を証明書ストアで検索する方法を指定します。サポートされる値: は、FindByThumbprint: 証明書で証明書 thumbprintFindBySubjectName を検索: サブジェクト識別名は、証明書のサブジェクト名に必要な FindValue、提供時にサブジェクトの識別名または共通名は、証明書が見つかりませんネイティブの Windows 暗号化 API の制限のためのエンコード ASN でエンコードされます。 FindValue で共通名が提供されている場合、このような制限はありません。</para>
        </summary>
        <value>
          <para>使用して、クラスターをセキュリティで保護するセキュリティ資格情報の種類。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindValue">
      <MemberSignature Language="C#" Value="public object FindValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FindValue" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.FindValue" />
      <MemberSignature Language="VB.NET" Value="Public Property FindValue As Object" />
      <MemberSignature Language="F#" Value="member this.FindValue : obj with get, set" Usage="System.Fabric.X509Credentials.FindValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>証明書ストア内のローカルの証明書の検索に使用されるフィルター値を指定します。 FindType では、フィルター値の型を指定します。</para>
        </summary>
        <value>
          <para>使用して、クラスターをセキュリティで保護するセキュリティ資格情報の値。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FindValueSecondary">
      <MemberSignature Language="C#" Value="public object FindValueSecondary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object FindValueSecondary" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.FindValueSecondary" />
      <MemberSignature Language="VB.NET" Value="Public Property FindValueSecondary As Object" />
      <MemberSignature Language="F#" Value="member this.FindValueSecondary : obj with get, set" Usage="System.Fabric.X509Credentials.FindValueSecondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはローカルの証明書資格情報を読み込むためのセカンダリの検索の値を設定します。</para>
        </summary>
        <value>
          <para>セカンダリでは、ローカルの証明書資格情報を読み込むための値を求めます。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssuerThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; IssuerThumbprints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; IssuerThumbprints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.IssuerThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IssuerThumbprints As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.IssuerThumbprints : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.X509Credentials.IssuerThumbprints" />
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
          <para>空でない場合は、リモート証明書の直接の発行者の証明書の拇印が決まります。</para>
        </summary>
        <value>
          <para>リモート証明書の直接の発行者の証明書の拇印。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionLevel">
      <MemberSignature Language="C#" Value="public System.Fabric.ProtectionLevel ProtectionLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ProtectionLevel ProtectionLevel" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.ProtectionLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionLevel As ProtectionLevel" />
      <MemberSignature Language="F#" Value="member this.ProtectionLevel : System.Fabric.ProtectionLevel with get, set" Usage="System.Fabric.X509Credentials.ProtectionLevel" />
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
          <para>ヘッダーと本文内のメッセージに、クラスターのノード間で送信されたときに適用された整合性と機密性を保証があるかどうかを指定するために使用する文字列値を示します。</para>
        </summary>
        <value>
          <para>ヘッダーと本文内のメッセージに、クラスターのノード間で送信されたときに適用された整合性と機密性を保証があるかどうかを指定するために使用する文字列値です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteCertThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; RemoteCertThumbprints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; RemoteCertThumbprints" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.RemoteCertThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteCertThumbprints As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.RemoteCertThumbprints : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.X509Credentials.RemoteCertThumbprints" />
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
          <para>リモート X509Credentials の検証に使用される、リモート証明書の拇印の一覧を取得します。</para>
        </summary>
        <value>
          <para>リモート X509Credentials の検証に使用される、リモート証明書の拇印の一覧</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteCommonNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; RemoteCommonNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; RemoteCommonNames" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.RemoteCommonNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteCommonNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.RemoteCommonNames : System.Collections.Generic.IList&lt;string&gt;" Usage="System.Fabric.X509Credentials.RemoteCommonNames" />
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
          <para>検証に使用する Service Fabric するリモートの証明書の共通名を予期されることを示します。</para>
        </summary>
        <value>
          <para>検証に使用する Service Fabric するリモートの証明書の必要な共通名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteX509Names">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.X509Name&gt; RemoteX509Names { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.X509Name&gt; RemoteX509Names" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.RemoteX509Names" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteX509Names As IList(Of X509Name)" />
      <MemberSignature Language="F#" Value="member this.RemoteX509Names : System.Collections.Generic.IList&lt;System.Fabric.X509Name&gt;" Usage="System.Fabric.X509Credentials.RemoteX509Names" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.X509Name&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>リモート X509Credentials を検証する X509Name の一覧を取得します。</para>
        </summary>
        <value>
          <para>リモート X509Credentials を検証する X509Name の一覧</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLocation">
      <MemberSignature Language="C#" Value="public System.Security.Cryptography.X509Certificates.StoreLocation StoreLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Security.Cryptography.X509Certificates.StoreLocation StoreLocation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.StoreLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreLocation As StoreLocation" />
      <MemberSignature Language="F#" Value="member this.StoreLocation : System.Security.Cryptography.X509Certificates.StoreLocation with get, set" Usage="System.Fabric.X509Credentials.StoreLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.X509Certificates.StoreLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>証明書ストアの場所を示します。</para>
        </summary>
        <value>
          <para>証明書ストアの場所。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string with get, set" Usage="System.Fabric.X509Credentials.StoreName" />
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
          <para>証明書が格納されているストアの名前を示します。</para>
        </summary>
        <value>
          <para>証明書が格納されているストアの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreNameDefault">
      <MemberSignature Language="C#" Value="public static string StoreNameDefault { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string StoreNameDefault" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.X509Credentials.StoreNameDefault" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property StoreNameDefault As String" />
      <MemberSignature Language="F#" Value="member this.StoreNameDefault : string" Usage="System.Fabric.X509Credentials.StoreNameDefault" />
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
          <para>証明書が格納されているストアの既定の名前を示します。</para>
        </summary>
        <value>
          <para>証明書が格納されているストアの既定の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>