<Type Name="NamespaceManager" FullName="Microsoft.Azure.NotificationHubs.NamespaceManager">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManager" />
  <TypeSignature Language="F#" Value="type NamespaceManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>キュー、トピック、サブスクリプション、およびサービスの名前空間内のルールなどのエンティティの管理に使用されるアンカー クラスを表します。 サービスの名前空間を管理するためにサービスの名前空間アドレスとアクセス資格情報を提供する必要があります。</summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
             NamespaceManagerSettings nsSettings = 新しい NamespaceManagerSettings() です。資格情報と操作タイムアウト NamespaceManager マネージャーを使って新しい NamespaceManager = (新しい Uri("baseUri")、NsSettings) です。
              </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の住所。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のアドレスを持つクラス。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">アドレス フィールドが null の場合にスローされます。</exception>
        <exception cref="T:System.ArgumentException">アドレスの一覧が null または空の場合にスローされます。</exception>
        <exception cref="T:System.UriFormatException">アドレスの形式が正しくない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の完全 URI アドレス。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラス。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">アドレス フィールドが null の場合にスローされます。</exception>
        <exception cref="T:System.ArgumentException">アドレスの一覧が null または空の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間の完全なアドレスです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間のアドレスを持つクラス。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">アドレスが null の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address">サービス名前空間の完全な URI アドレス。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラス。 </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">アドレスが null の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の住所。</param>
        <param name="settings">A<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" />と<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />プロパティです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />クラスを指定したアドレスと設定を使用します。</summary>
        <remarks>
            名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではないベース アドレス itse に指定した資格情報がある必要があります。lf
            </remarks>
        <exception cref="T:System.ArgumentNullException">場合にスローされるアドレスまたは設定が null です。</exception>
        <exception cref="T:System.ArgumentException">アドレスの一覧が null または空の場合にスローされます。</exception>
        <exception cref="T:System.UriFormatException">アドレスの形式が正しくない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の住所。</param>
        <param name="tokenProvider">セキュリティ トークン プロバイダー。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />クラスを指定したアドレスとトークン プロバイダーを使用します。</summary>
        <remarks>
            名前空間アドレスにパスを含めることはできません、場合でも、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定できます。
            </remarks>
        <exception cref="T:System.ArgumentNullException">アドレス フィールドが null の場合にスローされます。</exception>
        <exception cref="T:System.ArgumentException">アドレスの一覧が null または空の場合にスローされます。</exception>
        <exception cref="T:System.UriFormatException">アドレスの形式が正しくない場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の完全 URI アドレス。</param>
        <param name="settings">A<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" />と<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />プロパティです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />クラスが指定されたサービス名前空間 URI のベース アドレスと設定を使用します。</summary>
        <remarks>
            名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません必要がありますを指定する資格情報されるベース アドレスをself
            </remarks>
        <exception cref="T:System.ArgumentNullException">場合にスローされるアドレスや設定が null です。</exception>
        <exception cref="T:System.ArgumentException">アドレスの一覧が null または空の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の完全 URI アドレス。</param>
        <param name="tokenProvider">セキュリティ トークン プロバイダー。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />トークン プロバイダー、指定されたサービス名前空間 URI のベース アドレスを持つクラス。</summary>
        <remarks>
            名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません必要がありますを指定する資格情報されるベース アドレスをself
            </remarks>
        <exception cref="T:System.ArgumentNullException">アドレスが null の場合にスローされます。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">型がサポートされている資格情報の種類ではない場合にスローされます。
            参照してください<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />でサポートされる型の詳細を知るにします。</exception>
        <exception cref="T:System.ArgumentException">アドレスの一覧が null または空の場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String,Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間の完全なアドレスです。</param>
        <param name="settings">A<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" />と<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />プロパティです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間のベース アドレスを持つクラスと<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />オブジェクト。</summary>
        <remarks>
            名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません自体ベース アドレスを指定した資格情報がある必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> または <paramref name="settings" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String,Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間の完全なアドレスです。</param>
        <param name="tokenProvider">セキュリティ トークン プロバイダー。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />トークン プロバイダー、指定されたサービス名前空間のベース アドレスを持つクラス。</summary>
        <remarks>
            名前空間アドレスにパスを含めることはできません、場合でも、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定できます。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> または <paramref name="token provider" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri,Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address">サービス名前空間の完全な URI アドレス。</param>
        <param name="settings">A<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" />と<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" />プロパティです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラスと<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />オブジェクト。</summary>
        <remarks>
            名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません自体ベース アドレスを指定した資格情報がある必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> または <paramref name="settings" /> が null です。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri,Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">サービス名前空間の完全な URI アドレス。</param>
        <param name="tokenProvider">セキュリティ トークン プロバイダー オブジェクト。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラスと<see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" />オブジェクト。</summary>
        <remarks>
            名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません自体ベース アドレスを指定した資格情報がある必要があります。
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> または <paramref name="token provider" /> が null です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">型がサポートされている資格情報の種類ではない場合にスローされます。
            参照してください<see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" />でサポートされる型の詳細を知るにします。</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サービス名前空間のベース アドレスを取得します。</summary>
        <value>A<see cref="T:System.Uri" />サービス名前空間のベース アドレスを表すです。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVersionInfo">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetVersionInfo (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetVersionInfo(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.BeginGetVersionInfo(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetVersionInfo (callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetVersionInfo : AsyncCallback * obj -&gt; IAsyncResult" Usage="namespaceManager.BeginGetVersionInfo (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">操作の完了時に呼び出すメソッドを参照する <see cref="T:System.AsyncCallback" /> デリゲート。</param>
        <param name="state">非同期操作に関する状態情報を含むユーザー定義のオブジェクト。 このオブジェクトは、操作の完了時に <see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndGetVersioninfo(System.IAsyncResult)" /> デリゲートに渡されます。</param>
        <summary>非同期バージョンの<see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfo(System.String)" />メソッドです。</summary>
        <returns><see cref="T:System.IAsyncResult" />バージョン情報を取得する非同期操作を参照するオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NamespaceManager Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NamespaceManager Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> の新しいインスタンスを作成します。</summary>
        <returns><see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> の新しいインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NamespaceManager CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NamespaceManager CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">接続文字列を使用します。</param>
        <summary>新しいインスタンスを作成<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />指定された接続文字列を使用します。</summary>
        <returns><see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> の新しいインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription CreateNotificationHub (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription CreateNotificationHub(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateNotificationHub(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNotificationHub (description As NotificationHubDescription) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateNotificationHub : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.CreateNotificationHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">新しい通知ハブが作成される属性を記述する説明オブジェクト。</param>
        <summary>指定されたプロパティを持つ新しい通知ハブを作成、<paramref name="description" />パラメーター。</summary>
        <returns>A<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />新しく作成された通知ハブの説明を持つオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; CreateNotificationHubAsync (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; CreateNotificationHubAsync(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateNotificationHubAsync(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNotificationHubAsync (description As NotificationHubDescription) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateNotificationHubAsync : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.CreateNotificationHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">新しい通知ハブが作成される属性を記述する説明オブジェクト。</param>
        <summary>指定されたプロパティを持つ新しい通知ハブを非同期に作成、<paramref name="description" />パラメーター。</summary>
        <returns>A<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />新しく作成された通知ハブの説明を持つオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNotificationHub">
      <MemberSignature Language="C#" Value="public void DeleteNotificationHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNotificationHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.DeleteNotificationHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNotificationHub (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteNotificationHub : string -&gt; unit" Usage="namespaceManager.DeleteNotificationHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">通知ハブへのパス。</param>
        <summary>指定された通知ハブを削除<paramref name="path" />です。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNotificationHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNotificationHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.DeleteNotificationHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteNotificationHubAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteNotificationHubAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteNotificationHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">通知ハブへのパス。</param>
        <summary>指定された通知ハブを非同期に削除<paramref name="path" />です。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteInstallation">
      <MemberSignature Language="C#" Value="public void EndDeleteInstallation (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EndDeleteInstallation(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndDeleteInstallation(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub EndDeleteInstallation (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="member this.EndDeleteInstallation : IAsyncResult -&gt; unit" Usage="namespaceManager.EndDeleteInstallation result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">待機する保留状態の非同期要求への参照。</param>
        <summary>
            非同期の削除が保留中のインストールが完了するまで待機します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteRegistration">
      <MemberSignature Language="C#" Value="public void EndDeleteRegistration (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EndDeleteRegistration(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndDeleteRegistration(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub EndDeleteRegistration (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="member this.EndDeleteRegistration : IAsyncResult -&gt; unit" Usage="namespaceManager.EndDeleteRegistration result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />登録削除操作の結果を表すオブジェクト。</param>
        <summary>登録を削除する非同期の要求を終了します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetVersionInfo">
      <MemberSignature Language="C#" Value="public string EndGetVersionInfo (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string EndGetVersionInfo(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndGetVersionInfo(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetVersionInfo (result As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="member this.EndGetVersionInfo : IAsyncResult -&gt; string" Usage="namespaceManager.EndGetVersionInfo result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result"><see cref="T:System.IAsyncResult" />バージョン情報の取得の結果を表すオブジェクト。</param>
        <summary>バージョン情報を取得する非同期要求を終了します。</summary>
        <returns>バージョン情報です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription GetNotificationHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription GetNotificationHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHub (path As String) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHub : string -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.GetNotificationHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービスの名前空間へのパス。</param>
        <summary>サービスの名前空間から通知ハブの説明を取得します。</summary>
        <returns><see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />サービス名前空間からです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubAsync (path As String) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.GetNotificationHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービスの名前空間へのパス。</param>
        <summary>非同期的に、サービス名前空間から通知ハブの説明を取得します。</summary>
        <returns>サービスの名前空間から通知ハブの説明を取得する非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync (string jobId, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync(string jobId, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubJobAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobAsync (jobId As String, notificationHubPath As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="namespaceManager.GetNotificationHubJobAsync (jobId, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">ジョブの ID。</param>
        <param name="notificationHubPath">通知ハブへのパス。</param>
        <summary>指定された通知ハブのジョブを非同期に取得します。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync (string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync(string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubJobsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobsAsync (notificationHubPath As String) As Task(Of IEnumerable(Of NotificationHubJob))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;" Usage="namespaceManager.GetNotificationHubJobsAsync notificationHubPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notificationHubPath">通知ハブへのパス。</param>
        <summary>非同期的に一連のすべての通知ハブのジョブを取得します。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubs() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubs" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubs () As IEnumerable(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubs : unit -&gt; seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.GetNotificationHubs " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>サービスの名前空間から通知ハブの説明を取得します。</summary>
        <returns>サービスの名前空間からの通知ハブの説明の一覧。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt; GetNotificationHubsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt; GetNotificationHubsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubsAsync () As Task(Of IEnumerable(Of NotificationHubDescription))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt;" Usage="namespaceManager.GetNotificationHubsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>非同期的に、サービス名前空間から通知ハブの説明を取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfo">
      <MemberSignature Language="C#" Value="public string GetVersionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetVersionInfo() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfo () As String" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfo : unit -&gt; string" Usage="namespaceManager.GetVersionInfo " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>サーバーまたはサービスが処理できる最大のサポートされているプロトコルのバージョンを示す"YYYY MM"形式の文字列を取得します。</summary>
        <returns>サーバーまたはサービスが処理できる最大のサポートされているプロトコルのバージョンを示す文字列です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfoAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetVersionInfoAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetVersionInfoAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfoAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfoAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfoAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="namespaceManager.GetVersionInfoAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>非同期的に、サーバーまたはサービスが処理できる最大のサポートされているプロトコルのバージョンを示す"YYYY MM"形式の文字列を取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationHubExists">
      <MemberSignature Language="C#" Value="public bool NotificationHubExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool NotificationHubExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.NotificationHubExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function NotificationHubExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.NotificationHubExists : string -&gt; bool" Usage="namespaceManager.NotificationHubExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">通知ハブへのパス。</param>
        <summary>指定された通知ハブがあるかどうかを判断<paramref name="path" />サービス名前空間にします。</summary>
        <returns>内の指定した通知ハブがある場合は true。<paramref name="path" />サービス名前空間です。 それ以外の場合は false。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationHubExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NotificationHubExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NotificationHubExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.NotificationHubExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function NotificationHubExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NotificationHubExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.NotificationHubExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">通知ハブへのパス。</param>
        <summary>指定された通知ハブがあるかどうかを非同期に判断<paramref name="path" />サービス名前空間にします。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtocolVersion">
      <MemberSignature Language="C#" Value="public const string ProtocolVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ProtocolVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.NamespaceManager.ProtocolVersion" />
      <MemberSignature Language="VB.NET" Value="Public Const ProtocolVersion As String " />
      <MemberSignature Language="F#" Value="val mutable ProtocolVersion : string" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.ProtocolVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>クライアントのプロトコルのバージョンを示す"YYYY MM"の形式の文字列を指定します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NamespaceManagerSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As NamespaceManagerSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManagerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サービス名前空間のクライアント設定を取得します。</summary>
        <value>A<see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />サービス名前空間のクライアント設定を表すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync (Microsoft.Azure.NotificationHubs.NotificationHubJob job, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync(class Microsoft.Azure.NotificationHubs.NotificationHubJob job, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitNotificationHubJobAsync (job As NotificationHubJob, notificationHubPath As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.SubmitNotificationHubJobAsync : Microsoft.Azure.NotificationHubs.NotificationHubJob * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="namespaceManager.SubmitNotificationHubJobAsync (job, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.NotificationHubs.NotificationHubJob" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="job">A<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" />を送信するジョブを表すオブジェクト。</param>
        <param name="notificationHubPath">通知ハブへのパス。</param>
        <summary>処理の通知ハブのジョブを送信します。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription UpdateNotificationHub (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription UpdateNotificationHub(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.UpdateNotificationHub(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNotificationHub (description As NotificationHubDescription) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateNotificationHub : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.UpdateNotificationHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">通知ハブの更新する属性を記述する説明オブジェクト。</param>
        <summary>指定されたパスに、既存の通知ハブを更新、<paramref name="description" />パラメーター。 指定したで通知ハブのすべてのプロパティが上書きされます、<paramref name="description" />パラメーター。 </summary>
        <returns>A<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />更新された通知ハブの説明を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; UpdateNotificationHubAsync (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; UpdateNotificationHubAsync(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.UpdateNotificationHubAsync(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNotificationHubAsync (description As NotificationHubDescription) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateNotificationHubAsync : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.UpdateNotificationHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">通知ハブの更新する属性を記述する説明オブジェクト。</param>
        <summary>指定されたパスに、既存の通知ハブを非同期に更新、<paramref name="description" />パラメーター。 指定したで通知ハブのすべてのプロパティが上書きされます、<paramref name="description" />パラメーター。</summary>
        <returns>A<see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />更新された通知ハブの説明を表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>