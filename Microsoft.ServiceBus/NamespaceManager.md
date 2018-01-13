<Type Name="NamespaceManager" FullName="Microsoft.ServiceBus.NamespaceManager">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NamespaceManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManager" />
  <TypeSignature Language="F#" Value="type NamespaceManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
             NamespaceManagerSettings nsSettings = 新しい NamespaceManagerSettings() です。資格情報と操作タイムアウト NamespaceManager マネージャーを使って新しい NamespaceManager = (新しい Uri("baseUri")、nsSettings) です。
             </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;string&gt; -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の住所。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />特定のアドレスを持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;Uri&gt; -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の完全 URI アドレス。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : string -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間の完全なアドレスです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />特定のサービス名前空間のアドレスを持つクラス。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : Uri -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address">サービス名前空間の完全な URI アドレス。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラス。 </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;string&gt; * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の住所。</param>
        <param name="settings">A<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />と<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />プロパティです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />クラスを指定したアドレスと設定を使用します。</summary>
        <remarks>名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではないベース アドレス itse に指定した資格情報がある必要があります。lf です。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の住所。</param>
        <param name="tokenProvider">セキュリティ トークン プロバイダー。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />クラスを指定したアドレスとトークン プロバイダーを使用します。</summary>
        <remarks>名前空間アドレスにパスを含めることはできません、場合でも、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定できます。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;Uri&gt; * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の完全 URI アドレス。</param>
        <param name="settings">A<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />と<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />プロパティです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />クラスが指定されたサービス名前空間 URI のベース アドレスと設定を使用します。</summary>
        <remarks>名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません必要がありますを指定する資格情報されるベース アドレスをself です。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">サービス名前空間の完全 URI アドレス。</param>
        <param name="tokenProvider">セキュリティ トークン プロバイダー。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />トークン プロバイダー、指定されたサービス名前空間 URI のベース アドレスを持つクラス。</summary>
        <remarks>名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません必要がありますを指定する資格情報されるベース アドレスをself です。</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.String,Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : string * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間の完全なアドレスです。</param>
        <param name="settings">A<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />と<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />プロパティです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />特定のサービス名前空間のベース アドレスを持つクラスと<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />オブジェクト。</summary>
        <remarks>名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません自体ベース アドレスを指定した資格情報がある必要があります。</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> または <paramref name="settings" /> が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : string * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">サービスの名前空間の完全なアドレスです。</param>
        <param name="tokenProvider">セキュリティ トークン プロバイダー。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />トークン プロバイダー、指定されたサービス名前空間のベース アドレスを持つクラス。</summary>
        <remarks>名前空間アドレスにパスを含めることはできません、場合でも、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定できます。</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> または <paramref name="tokenProvider" /> が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Uri,Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : Uri * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address">サービス名前空間の完全な URI アドレス。</param>
        <param name="settings">A<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />含むオブジェクトを<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />と<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />プロパティです。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラスと<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />オブジェクト。</summary>
        <remarks>名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません自体ベース アドレスを指定した資格情報がある必要があります。</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> または <paramref name="settings" /> が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : Uri * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">サービス名前空間の完全な URI アドレス。</param>
        <param name="tokenProvider">セキュリティ トークン プロバイダー オブジェクト。</param>
        <summary>新しいインスタンスを初期化、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />特定のサービス名前空間 URI のベース アドレスを持つクラスと<see cref="T:Microsoft.ServiceBus.TokenProvider" />オブジェクト。</summary>
        <remarks>名前空間アドレスにパスを含めることはできません、ベース アドレスから下位レベルの一部に対してのみ操作を実行することを承認する資格情報を指定することができますが、つまりではありません自体ベース アドレスを指定した資格情報がある必要があります。</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />サービスの名前空間の完全なアドレスに追加のパスが含まれています。</exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> または <paramref name="tokenProvider" /> が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NamespaceManager.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.ServiceBus.NamespaceManager.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.NamespaceManager Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.NamespaceManager Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="Microsoft.ServiceBus.NamespaceManager.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><see cref="T:Microsoft.ServiceBus.NamespaceManager" /> の新しいインスタンスを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.NamespaceManager" /> の新しいインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroup (description As ConsumerGroupDescription) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroup : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroup description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />。</param>
        <summary>使用して、指定されたイベント ハブ コンシューマー グループを作成<see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />です。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroup (eventHubPath As String, name As String) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroup : string * string -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroup (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="name">コンシューマー グループの名前。</param>
        <summary>指定された Event Hubs パスと、コンシューマー グループの名前で、既定値を使用し、Event Hubs コンシューマー グループを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupAsync(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupAsync (description As ConsumerGroupDescription) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupAsync : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />。</param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" /> の非同期バージョン。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupAsync (eventHubPath As String, name As String) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="name">コンシューマー グループの名前。</param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(System.String,System.String)" /> の非同期バージョン。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExists (description As ConsumerGroupDescription) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExists : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroupIfNotExists description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> オブジェクト。</param>
        <summary>既になくても、使用して、指定した場合、コンシューマー グループを作成<see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />メタデータとして。 グループが既に存在する場合を返すし、格納されている<see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />です。</summary>
        <returns>新たに作成されたを返します<see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />です。 コンシューマー グループが既に存在する場合は、既存を返します。<see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExists (eventHubPath As String, name As String) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExists : string * string -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroupIfNotExists (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="name">作成するコンシューマー グループの名前です。</param>
        <summary>既になくても、指定された Event Hubs のパスとグループ名を使用する場合は、コンシューマー グループを作成します。 グループが既に存在する場合を返すし、格納されている<see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />です。</summary>
        <returns>新たに作成されたを返します<see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />です。 コンシューマー グループが既に存在する場合は、既存を返します。<see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExistsAsync(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExistsAsync (description As ConsumerGroupDescription) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExistsAsync : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupIfNotExistsAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description">コンシューマー グループの説明。</param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" /> の非同期バージョン。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExistsAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExistsAsync (eventHubPath As String, name As String) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExistsAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupIfNotExistsAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="name">コンシューマー グループの名前。</param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(System.String,System.String)" /> の非同期バージョン。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHub(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHub (description As EventHubDescription) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHub : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />。</param>
        <summary>指定されたを使用して、新しいイベント ハブを作成<see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />です。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHub (path As String) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHub : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Event Hub へのパス。</param>
        <summary>既定値、指定された入力パスを使用して、新しいイベント ハブを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubAsync(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubAsync (description As EventHubDescription) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubAsync : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Event Hub を作成するを記述するオブジェクト。</param>
        <summary>非同期に event hub を作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubAsync (path As String) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Event Hub へのパス。</param>
        <summary>非同期に event hub を作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExists(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExists (description As EventHubDescription) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExists : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHubIfNotExists description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Event Hub を作成するを記述するオブジェクト。</param>
        <summary>存在しない場合は、Event Hub を作成します。</summary>
        <returns>返します、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExists (path As String) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExists : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHubIfNotExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Event Hub へのパス。</param>
        <summary>存在しない場合は、Event Hub を作成します。</summary>
        <returns>返します、<see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExistsAsync(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExistsAsync (description As EventHubDescription) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExistsAsync : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubIfNotExistsAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">イベント ハブの説明。</param>
        <summary>非同期的が存在しない場合は、Event Hub を作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExistsAsync (path As String) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubIfNotExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">イベント ハブのパス。</param>
        <summary>非同期的が存在しない場合は、Event Hub を作成します。</summary>
        <returns>非同期操作を完了するタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.NamespaceManager CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.NamespaceManager CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="Microsoft.ServiceBus.NamespaceManager.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">接続文字列を使用します。</param>
        <summary>新しいインスタンスを作成<see cref="T:Microsoft.ServiceBus.NamespaceManager" />指定された接続文字列を使用します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.NamespaceManager" /> の新しいインスタンス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueue(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueue (description As QueueDescription) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.CreateQueue : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.CreateQueue description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />新しいキューが作成される属性を記述するオブジェクト。</param>
        <summary>指定したキューの説明を持つサービスの名前空間に新しいキューを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />新しく作成されたキューのです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueue (path As String) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.CreateQueue : string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.CreateQueue path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <summary>指定されたパスでサービス名前空間に新しいキューを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />新しく作成されたキューのです。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />null または空です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">長さ<paramref name="path" />290 文字より長い。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きく必要があります、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">キューまたはトピックを同じ名前とパスは、同じサービス名前空間で存在します。</exception>
        <exception cref="T:System.UnauthorizedAccessException"><see cref="T:Microsoft.ServiceBus.NamespaceManager" />オブジェクトには、この操作を実行するための十分なアクセス許可はありません。 されることを確認する必要があります、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />が正しい<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />資格情報、操作を実行します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException">説明で指定されたサイズはサポートされていませんか、最大許容クォータに達しました。 サポートされているサイズの値のいずれかを指定、既存のエンティティを削除、または、クォータ サイズを大きく必要があります。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">サーバーは論理操作でオーバー ロードします。 次の操作: 待機のいずれかを検討してくださいでき、この関数の呼び出しを再試行してください。再試行の前にエンティティを削除する (それ以上送信する前に、メッセージを受信など)。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueueAsync(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueueAsync (description As QueueDescription) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateQueueAsync : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.CreateQueueAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />新しいキューが作成される属性を記述するオブジェクト。</param>
        <summary>非同期的に、指定したキューの説明と、サービス名前空間に新しいキューを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />新しく作成されたキューのです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueueAsync (path As String) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateQueueAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.CreateQueueAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <summary>非同期的に指定されたパスでサービス名前空間に新しいキューを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />新しく作成されたキューのです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelay(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelay (description As RelayDescription) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.CreateRelay : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.CreateRelay description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description">新しいリレーを作成する属性を記述する説明オブジェクト。</param>
        <summary>指定されたリレーの説明を持つサービスの名前空間に新しいリレーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" />新しく作成されたリレーのオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay (string path, Microsoft.ServiceBus.RelayType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay(string path, valuetype Microsoft.ServiceBus.RelayType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelay(System.String,Microsoft.ServiceBus.RelayType)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelay (path As String, type As RelayType) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.CreateRelay : string * Microsoft.ServiceBus.RelayType -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.CreateRelay (path, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.ServiceBus.RelayType" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <param name="type">リレー型です。</param>
        <summary>指定したパスおよび型を持つサービスの名前空間に新しいリレーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" />新しく作成されたリレーのオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelayAsync(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelayAsync (description As RelayDescription) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateRelayAsync : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.CreateRelayAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description">新しいリレーを作成する属性を記述する説明オブジェクト。</param>
        <summary>非同期的に指定されたリレーの説明を持つサービスの名前空間に新しいリレーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" />新しく作成されたリレーのオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync (string path, Microsoft.ServiceBus.RelayType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync(string path, valuetype Microsoft.ServiceBus.RelayType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelayAsync(System.String,Microsoft.ServiceBus.RelayType)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelayAsync (path As String, type As RelayType) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateRelayAsync : string * Microsoft.ServiceBus.RelayType -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.CreateRelayAsync (path, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.ServiceBus.RelayType" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <param name="type">リレー型です。</param>
        <summary>非同期的に指定されたパスおよび型を持つサービスの名前空間に新しいリレーを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" />新しく作成されたリレーのオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscription (description As SubscriptionDescription) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />を新しいサブスクリプションが作成される属性を記述するオブジェクト。</param>
        <summary>指定したサブスクリプションの説明を持つサービスの名前空間に新しいサブスクリプションを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />新しく作成されたサブスクリプションのです。</returns>
        <remarks> 既定値をするには、このサブスクリプションでは、すべてのメッセージをこのサブスクリプションに移動できるようになりますが、「パススルー」フィルターが作成されます。 フィルターの名前は<see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.Filter -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (description, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />を新しいサブスクリプションが作成される属性を記述するオブジェクト。</param>
        <param name="filter">フィルター式の値を満たすメッセージをキャプチャするために使用するフィルター式です。</param>
        <summary>指定されたサブスクリプションの説明とフィルター式をサービス名前空間に新しいサブスクリプションを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />新しく作成されたサブスクリプションのです。</returns>
        <remarks> 既定のルールは、データを使用して作成されます<paramref name="filter" />として名前付き<see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />します。 </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (description, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />を新しいサブスクリプションが作成される属性を記述するオブジェクト。</param>
        <param name="ruleDescription">A<see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" />属性をメッセージは、一致の受け入れと処理を記述するオブジェクト。</param>
        <summary>指定されたサブスクリプションの説明、規則の説明とサービスの名前空間に新しいサブスクリプションを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />新しく作成されたサブスクリプションのです。</returns>
        <remarks> 既定のルールは、データを使用して作成されます<paramref name="ruleDescription" />です。
            場合<see cref="P:Microsoft.ServiceBus.Messaging.RuleDescription.Name" />が null または空白文字、作成したルールの名前になります<see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />です。 </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscription (topicPath As String, name As String) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <summary>指定したトピックのパスとサブスクリプションの名前を持つサービスの名前空間に新しいサブスクリプションを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />新しく作成されたサブスクリプションのです。</returns>
        <remarks> 既定値をするには、このサブスクリプションでは、すべてのメッセージをこのサブスクリプションに移動できるようになりますが、「パススルー」フィルターが作成されます。 フィルターの名前は<see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />します。</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (string topicPath, string name, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(string topicPath, string name, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(System.String,System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : string * string * Microsoft.ServiceBus.Messaging.Filter -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (topicPath, name, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <param name="filter">フィルター式の値を満たすメッセージをキャプチャするために使用するフィルター式です。</param>
        <summary>パスの指定したトピック、サブスクリプション名、およびフィルター式を持つサービス名前空間に新しいサブスクリプションを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />新しく作成されたサブスクリプションのです。</returns>
        <remarks> 既定のルールは、データを使用して作成されます<paramref name="filter" />として名前付き<see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />します。 </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (string topicPath, string name, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(string topicPath, string name, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(System.String,System.String,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : string * string * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (topicPath, name, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <param name="ruleDescription">A<see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" />属性をメッセージは、一致の受け入れと処理を記述するオブジェクト。</param>
        <summary>指定されたトピック、サブスクリプションの名前とパス規則の説明とサービスの名前空間に新しいサブスクリプションを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />新しく作成されたサブスクリプションのです。</returns>
        <remarks> 既定のルールは、データを使用して作成されます<paramref name="ruleDescription" />です。
            場合<see cref="P:Microsoft.ServiceBus.Messaging.RuleDescription.Name" />が null または空白文字、作成したルールの名前になります<see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />です。 </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscriptionAsync (description As SubscriptionDescription) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />を新しいサブスクリプションが作成される属性を記述するオブジェクト。</param>
        <summary>指定したサブスクリプションの説明を持つサービス名前空間に新しいサブスクリプションを非同期に作成します。</summary>
        <returns>非同期に作成されるサブスクリプション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.Filter -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (description, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />を新しいサブスクリプションが作成される属性を記述するオブジェクト。</param>
        <param name="filter">フィルター式の値を満たすメッセージをキャプチャするために使用するフィルター式です。</param>
        <summary>指定されたサブスクリプションの説明とフィルター式をサービス名前空間に新しいサブスクリプションを非同期に作成します。</summary>
        <returns>非同期に作成されるサブスクリプション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (description, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />を新しいサブスクリプションが作成される属性を記述するオブジェクト。</param>
        <param name="ruleDescription">A<see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" />属性をメッセージは、一致の受け入れと処理を記述するオブジェクト。</param>
        <summary>指定されたサブスクリプションの説明、規則の説明と、サービス名前空間に新しいサブスクリプションを非同期に作成します。</summary>
        <returns>非同期に作成されるサブスクリプション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscriptionAsync (topicPath As String, name As String) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <summary>指定したトピックのパスとサブスクリプションの名前を持つサービス名前空間に新しいサブスクリプションを非同期に作成します。</summary>
        <returns>非同期に作成されるサブスクリプション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (string topicPath, string name, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(string topicPath, string name, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(System.String,System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : string * string * Microsoft.ServiceBus.Messaging.Filter -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (topicPath, name, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <param name="filter">フィルター式の値を満たすメッセージをキャプチャするために使用するフィルター式です。</param>
        <summary>パスの指定したトピック、サブスクリプション名、およびフィルター式を持つサービス名前空間で新しいサブスクリプションを非同期に作成します。</summary>
        <returns>非同期に作成されるサブスクリプション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (string topicPath, string name, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(string topicPath, string name, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(System.String,System.String,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : string * string * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (topicPath, name, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <param name="ruleDescription">A<see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" />属性をメッセージは、一致の受け入れと処理を記述するオブジェクト。</param>
        <summary>指定されたトピック、サブスクリプションの名前とパス規則の説明とサービスの名前空間で新しいサブスクリプションを非同期に作成します。</summary>
        <returns>非同期に作成されるサブスクリプション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopic(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopic (description As TopicDescription) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.CreateTopic : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.CreateTopic description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />の新しいトピックが作成される属性を記述するオブジェクト。</param>
        <summary>指定したトピックの説明をサービス名前空間内の新しいトピックを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />の新しく作成されたトピック。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopic (path As String) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.CreateTopic : string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.CreateTopic path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>指定されたサービス名前空間のパスをサービス名前空間内の新しいトピックを作成します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />の新しく作成されたトピック。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />null または空、または<paramref name="path" />で開始または終了「/」です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">長さ<paramref name="path" />がより大きい<see cref="F:Microsoft.ServiceBus.Messaging.Constants.QueueNameMaximumLength" />です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きく必要があります、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">キューまたはトピックを同じ名前とパスは、同じサービス名前空間で存在します。</exception>
        <exception cref="T:System.UnauthorizedAccessException"><see cref="T:Microsoft.ServiceBus.NamespaceManager" />オブジェクトには、この操作を実行するための十分なアクセス許可はありません。 されることを確認する必要があります、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />が正しい<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />資格情報、操作を実行します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException">説明で指定されたサイズはサポートされていませんか、最大許容クォータに達しました。 サポートされているサイズの値のいずれかを指定、既存のエンティティを削除、または、クォータ サイズを大きく必要があります。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopicAsync(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopicAsync (description As TopicDescription) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateTopicAsync : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.CreateTopicAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />の新しいトピックが作成される属性を記述するオブジェクト。</param>
        <summary>非同期的に、指定したトピックの説明をサービス名前空間内の新しいトピックを作成します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopicAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopicAsync (path As String) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateTopicAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.CreateTopicAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>非同期的に指定されたサービス名前空間のパスをサービス名前空間内の新しいトピックを作成します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteConsumerGroup">
      <MemberSignature Language="C#" Value="public void DeleteConsumerGroup (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteConsumerGroup(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteConsumerGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteConsumerGroup (eventHubPath As String, name As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteConsumerGroup : string * string -&gt; unit" Usage="namespaceManager.DeleteConsumerGroup (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="name">削除するコンシューマー グループの名前です。</param>
        <summary>コンシューマー グループを削除します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteConsumerGroupAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteConsumerGroupAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteConsumerGroupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteConsumerGroupAsync (eventHubPath As String, name As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteConsumerGroupAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteConsumerGroupAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="name">削除するコンシューマー グループの名前です。</param>
        <summary>コンシューマー グループを非同期に削除します。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHub">
      <MemberSignature Language="C#" Value="public void DeleteEventHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteEventHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteEventHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteEventHub (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteEventHub : string -&gt; unit" Usage="namespaceManager.DeleteEventHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Event Hub へのパス。</param>
        <summary>Event Hub を削除します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteEventHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteEventHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteEventHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteEventHubAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteEventHubAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteEventHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Event Hub へのパス。</param>
        <summary>非同期に Event Hub を削除します。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteQueue">
      <MemberSignature Language="C#" Value="public void DeleteQueue (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteQueue(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteQueue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteQueue (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteQueue : string -&gt; unit" Usage="namespaceManager.DeleteQueue path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <summary>サービス名前空間のベース アドレスに対する相対パスで説明されているキューを削除します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />空または null、または<paramref name="path" />先頭または末尾が「/」です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">長さ<paramref name="path" />がより大きい<see cref="F:Microsoft.ServiceBus.Messaging.Constants.QueueNameMaximumLength" />です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きく必要があります、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">キューがこのパスの下に存在しません。</exception>
        <exception cref="T:System.UnauthorizedAccessException"><see cref="T:Microsoft.ServiceBus.NamespaceManager" />オブジェクトには、この操作を実行するための十分なアクセス許可はありません。 されることを確認する必要があります、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />が正しい<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />資格情報、操作を実行します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteQueueAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteQueueAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteQueueAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteQueueAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteQueueAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <summary>サービス名前空間のベース アドレスに対する相対パスで説明されているキューを非同期に削除します。</summary>
        <returns>キューの操作を非同期に削除します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRelay">
      <MemberSignature Language="C#" Value="public void DeleteRelay (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteRelay(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteRelay(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteRelay (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteRelay : string -&gt; unit" Usage="namespaceManager.DeleteRelay path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">リレー サービスの名前空間のベース アドレスに対する相対パス。</param>
        <summary>サービス名前空間のベース アドレスに対する相対パスで説明されているリレーを削除します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRelayAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRelayAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteRelayAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRelayAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRelayAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteRelayAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">リレー サービスの名前空間のベース アドレスに対する相対パス。</param>
        <summary>サービス名前空間のベース アドレスに対する相対パスで説明されているリレーを非同期に削除します。</summary>
        <returns>リレーの操作を非同期に削除します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSubscription">
      <MemberSignature Language="C#" Value="public void DeleteSubscription (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteSubscription(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteSubscription(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteSubscription (topicPath As String, name As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteSubscription : string * string -&gt; unit" Usage="namespaceManager.DeleteSubscription (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="name">削除するサブスクリプションの名前。</param>
        <summary>指定したトピックのパスとサブスクリプションの名前を持つサブスクリプションを削除します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteSubscriptionAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteSubscriptionAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteSubscriptionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteSubscriptionAsync (topicPath As String, name As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteSubscriptionAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteSubscriptionAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="name">削除するサブスクリプションの名前。</param>
        <summary>指定したトピックのパスとサブスクリプションの名前を持つサブスクリプションを非同期に削除します。</summary>
        <returns>サブスクリプションの操作を非同期に削除します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTopic">
      <MemberSignature Language="C#" Value="public void DeleteTopic (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteTopic(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteTopic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteTopic (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteTopic : string -&gt; unit" Usage="namespaceManager.DeleteTopic path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>サービス名前空間のベース アドレスに対する相対パスで説明したトピックを削除します。</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />null または空、または<paramref name="path" />先頭または末尾が「/」です。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteTopicAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteTopicAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteTopicAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteTopicAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteTopicAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteTopicAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>サービス名前空間のベース アドレスに対する相対パスで説明したトピックを非同期に削除します。</summary>
        <returns>トピックの操作を非同期に削除されます。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubExists">
      <MemberSignature Language="C#" Value="public bool EventHubExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool EventHubExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.EventHubExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function EventHubExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.EventHubExists : string -&gt; bool" Usage="namespaceManager.EventHubExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Event Hub へのパス。</param>
        <summary>イベント ハブが存在するかどうかを示します。</summary>
        <returns>イベント ハブが存在する場合、true を返しますそれ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; EventHubExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; EventHubExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.EventHubExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function EventHubExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EventHubExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.EventHubExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">イベント ハブのパス。</param>
        <summary>サービスの名前空間からイベント ハブが存在するかどうかを非同期に判断します。 </summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription GetConsumerGroup (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription GetConsumerGroup(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroup (eventHubPath As String, name As String) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroup : string * string -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.GetConsumerGroup (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="name">コンシューマー グループの名前。</param>
        <summary>イベント ハブ コンシューマー グループを取得します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroupAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroupAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroupAsync (eventHubPath As String, name As String) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroupAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.GetConsumerGroupAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="name">コンシューマー グループの名前。</param>
        <summary>コンシューマー グループを非同期に取得します。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroups (string eventHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroups(string eventHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroups(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroups (eventHubPath As String) As IEnumerable(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroups : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.GetConsumerGroups eventHubPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <summary>コンシューマー グループのセットを表すコレクションを取得します。</summary>
        <returns>返します、<see cref="T:System.Collections.Generic.IEnumerable`1" />コンシューマー グループのセットを表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroupsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt; GetConsumerGroupsAsync (string eventHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt; GetConsumerGroupsAsync(string eventHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroupsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroupsAsync (eventHubPath As String) As Task(Of IEnumerable(Of ConsumerGroupDescription))" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroupsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt;" Usage="namespaceManager.GetConsumerGroupsAsync eventHubPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <summary>コンシューマー グループのセットを非同期に取得します。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription GetEventHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription GetEventHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHub (path As String) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.GetEventHub : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.GetEventHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Event Hub へのパス。</param>
        <summary>Event Hub に関する情報を取得します。</summary>
        <returns>返します、 <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Event Hub の説明を含むオブジェクトです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubAsync (path As String) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.GetEventHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Event Hub へのパス。</param>
        <summary>Event Hub に関する情報を非同期に取得します。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartition">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartition (eventHubPath As String, name As String) As PartitionDescription" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartition : string * string -&gt; Microsoft.ServiceBus.Messaging.PartitionDescription" Usage="namespaceManager.GetEventHubPartition (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="name">Event Hub のパーティションの ID。</param>
        <summary>指定した Event Hub のパーティションに関する情報を返します。 このメソッドは、パーティションのパーティションの情報で指定することを想定しています、<paramref name="name" />によって示される既定のコンシューマー グループに属するパラメーター<paramref name="eventHubPath" />です。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.PartitionDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartition">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition (string eventHubPath, string consumerGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition(string eventHubPath, string consumerGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartition (eventHubPath As String, consumerGroupName As String, name As String) As PartitionDescription" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartition : string * string * string -&gt; Microsoft.ServiceBus.Messaging.PartitionDescription" Usage="namespaceManager.GetEventHubPartition (eventHubPath, consumerGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"></param>
        <param name="consumerGroupName"></param>
        <param name="name"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartitionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartitionAsync (eventHubPath As String, name As String) As Task(Of PartitionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartitionAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;" Usage="namespaceManager.GetEventHubPartitionAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="name">Event Hub のパーティションの ID。</param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync (string eventHubPath, string consumerGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync(string eventHubPath, string consumerGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartitionAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartitionAsync (eventHubPath As String, consumerGroupName As String, name As String) As Task(Of PartitionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartitionAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;" Usage="namespaceManager.GetEventHubPartitionAsync (eventHubPath, consumerGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Event Hub へのパス。</param>
        <param name="consumerGroupName">イベント ハブ コンシューマー グループの名前。</param>
        <param name="name">Event Hubs のパーティションの ID。</param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubs() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubs" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubs () As IEnumerable(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubs : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.GetEventHubs " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Event Hubs のセットを表すコレクションを取得します。</summary>
        <returns>返します、 <see cref="T:System.Collections.Generic.IEnumerable`1" /> Event Hubs のセットを表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt; GetEventHubsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt; GetEventHubsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubsAsync () As Task(Of IEnumerable(Of EventHubDescription))" />
      <MemberSignature Language="F#" Value="member this.GetEventHubsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt;" Usage="namespaceManager.GetEventHubsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Event Hubs の一覧を非同期に取得します。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription GetQueue (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription GetQueue(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueue (path As String) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.GetQueue : string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.GetQueue path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <summary>サービスの名前空間からキューを取得します。</summary>
        <returns>A <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> 、キューへのハンドルまたは<see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" />サービス名前空間にキューが存在しない場合は例外です。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />空または null、または<paramref name="path" />先頭または末尾が「/」です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きく必要があります、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:System.UnauthorizedAccessException"><see cref="T:Microsoft.ServiceBus.NamespaceManager" />オブジェクトには、この操作を実行するための十分なアクセス許可はありません。 されることを確認する必要があります、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />が正しい<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />資格情報、操作を実行します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">サービス名前空間にキューがありませんでした。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueueAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueueAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueueAsync (path As String) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.GetQueueAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.GetQueueAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <summary>非同期的に、サービス名前空間からキューを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueues" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueues () As IEnumerable(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.GetQueues : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.GetQueues " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>サービスの名前空間内のすべてのキューの列挙可能なコレクションを取得します。</summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerable`1" />サービス名前空間にキューまたはキューが存在しない場合は、空のコレクションを返しますのすべてのコレクションを表すオブジェクト。 </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きく必要があります、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:System.UnauthorizedAccessException"><see cref="T:Microsoft.ServiceBus.NamespaceManager" />オブジェクトには、この操作を実行するための十分なアクセス許可はありません。 されることを確認する必要があります、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />が正しい<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />資格情報、操作を実行します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetQueues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueues(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueues (filter As String) As IEnumerable(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.GetQueues : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.GetQueues filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">取得するキューをフィルター処理に使用する文字列。</param>
        <summary>指定したフィルターには、サービスの名前空間内のすべてのキューの列挙可能なコレクションを取得します。 エンティティの名前 (など語句で始まる)、エンティティの長さ (Gt または長期)、作成、更新、およびアクセス時刻 (Gt または長期) の組み合わせによってフィルター処理することができます。</summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerable`1" />サービス名前空間にキューまたはキューが存在しない場合は、空のコレクションを返しますのすべてのコレクションを表すオブジェクト。</returns>
        <remarks>
            式の形式をフィルター処理: {プロパティ} {論理演算子、{value}} {フィルター式} と {関数} {論理演算子、{value}} {フィルター式} と
                                        -----------------------------------------------------------------------------------------
            使用可能なプロパティ: パス |ModifiedAt |AccessedAt |CreatedAt |MessageCount 論理演算子: Eq |Ne |Gt |Ge |Lt |Le  
            値: 型関数の対応するプロパティの値: startswith ({プロパティ} {value})
            </remarks>
        <example>
          <code>
            var queuesWithMessages = namespaceManager.GetQueues ("messageCount Gt 0") です。var queuesStartsWith = namespaceManager.GetQueues ($"startswith (パス、'キュー') eq true") です。
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetQueuesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueuesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueuesAsync () As Task(Of IEnumerable(Of QueueDescription))" />
      <MemberSignature Language="F#" Value="member this.GetQueuesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;" Usage="namespaceManager.GetQueuesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>非同期的にサービスの名前空間内のすべてのキューの列挙可能なコレクションを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueuesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueuesAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueuesAsync (filter As String) As Task(Of IEnumerable(Of QueueDescription))" />
      <MemberSignature Language="F#" Value="member this.GetQueuesAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;" Usage="namespaceManager.GetQueuesAsync filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">取得するキューをフィルター処理に使用する文字列。</param>
        <summary>非同期的に指定されたフィルターを使用してサービスの名前空間内のすべてのキューの列挙可能なコレクションを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>
            式の形式をフィルター処理: {プロパティ} {論理演算子、{value}} {フィルター式} と {関数} {論理演算子、{value}} {フィルター式} と
                                        -----------------------------------------------------------------------------------------
            使用可能なプロパティ: パス |ModifiedAt |AccessedAt |CreatedAt |MessageCount 論理演算子: Eq |Ne |Gt |Ge |Lt |Le  
            値: 型関数の対応するプロパティの値: startswith ({プロパティ} {value})
            </remarks>
        <example>
          <code>
            var queuesWithMessages = await namespaceManager.GetQueuesAsync ("messageCount Gt 0") です。var queuesStartsWith = await namespaceManager.GetQueuesAsync ($"startswith (パス、'キュー') eq true") です。
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription GetRelay (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription GetRelay(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelay(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelay (path As String) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.GetRelay : string -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.GetRelay path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">リレー パスです。</param>
        <summary>特定のリレー エンドポイントの詳細を取得します。</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelayAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelayAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelayAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelayAsync (path As String) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRelayAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.GetRelayAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">リレー パスです。</param>
        <summary>非同期的に、特定のリレー エンドポイントの詳細を取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRelays">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelays ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelays() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelays" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelays () As IEnumerable(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRelays : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.GetRelays " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>すべてのリレー サービスの名前空間内のコレクションを取得します。</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRelaysAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt; GetRelaysAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt; GetRelaysAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelaysAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelaysAsync () As Task(Of IEnumerable(Of RelayDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRelaysAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt;" Usage="namespaceManager.GetRelaysAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceBus.NamespaceManager/&lt;GetRelaysAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>非同期的にすべてのリレー サービスの名前空間内のコレクションを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRevokedPublishers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; GetRevokedPublishers (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; GetRevokedPublishers(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRevokedPublishers(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRevokedPublishers (entityPath As String) As IEnumerable(Of RevokedPublisherDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRevokedPublishers : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;" Usage="namespaceManager.GetRevokedPublishers entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Event Hub へのパス。 以下を参照してください。<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" /></param>
        <summary>Event Hub で失効したすべてのパブリッシャーを返します。</summary>
        <returns>返します、<see cref="T:System.Collections.Generic.IEnumerable`1" />失効した発行元を含むコレクション。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRevokedPublishersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt; GetRevokedPublishersAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt; GetRevokedPublishersAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRevokedPublishersAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRevokedPublishersAsync (entityPath As String) As Task(Of IEnumerable(Of RevokedPublisherDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRevokedPublishersAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt;" Usage="namespaceManager.GetRevokedPublishersAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Event Hub へのパス。 以下を参照してください。<see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" /></param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.GetRevokedPublishers(System.String)" /> の非同期バージョン。</summary>
        <returns>返します、<see cref="T:System.Threading.Tasks.Task`1" />失効した発行元を格納します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRules(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRules (topicPath As String, subscriptionName As String) As IEnumerable(Of RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRules : string * string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;" Usage="namespaceManager.GetRules (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <param name="subscriptionName">サブスクリプションの名前。</param>
        <summary>サービスの名前空間のすべてのルールの列挙可能なコレクションを取得します。</summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerable`1" />サービス名前空間でルールまたはルールが存在しない場合は、空のコレクションを返しますのすべてのコレクションを表すオブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules (string topicPath, string subscriptionName, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules(string topicPath, string subscriptionName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRules(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRules (topicPath As String, subscriptionName As String, filter As String) As IEnumerable(Of RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRules : string * string * string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;" Usage="namespaceManager.GetRules (topicPath, subscriptionName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="subscriptionName">サブスクリプションの名前。</param>
        <param name="filter">取得するルールをフィルター処理に使用する文字列。</param>
        <summary>指定されたトピック パス、サブスクリプションの名前とフィルターで、サービス名前空間のすべてのルールの列挙可能なコレクションを取得します。</summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerable`1" />サービス名前空間でルールまたはルールが存在しない場合は、空のコレクションを返しますのすべてのコレクションを表すオブジェクト。</returns>
        <remarks>
            <a name="filter-expression-format---propery-logical-operator-value-filter-expression"></a>フィルター式の形式: {プロパティ} {論理演算子、{value} {フィルター式}}
            -----------------------------------------------------------------------------------------
            使用可能なプロパティ: ModifiedAt |AccessedAt |CreatedAt 論理演算子: Eq |Ne |Gt |Ge |Lt |Le  
            値: 対応するプロパティの型の値。
            </remarks>
        <example>
          <code>
            var fiveMinutesAgo DateTime.UtcNow.AddMinutes(-5) を = です。ToString ("M/dd/yyyy hh:mm:ss") です。var rulesInTheLast5Minutes = namespaceManager.GetRules (topicName、subscriptionName、$"createdAt gt '{fiveMinutesAgo}'") です。
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRulesAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync (topicPath As String, subscriptionName As String) As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRulesAsync : string * string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;" Usage="namespaceManager.GetRulesAsync (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="subscriptionName">サブスクリプションの名前。</param>
        <summary>非同期的に、サービス名前空間のすべてのルールの列挙可能なコレクションを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync (string topicPath, string subscriptionName, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync(string topicPath, string subscriptionName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRulesAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync (topicPath As String, subscriptionName As String, filter As String) As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRulesAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;" Usage="namespaceManager.GetRulesAsync (topicPath, subscriptionName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスの基準としたトピック パス。</param>
        <param name="subscriptionName">サブスクリプションの名前。</param>
        <param name="filter">取得するルールをフィルター処理に使用する文字列。</param>
        <summary>非同期的に指定されたトピック パス、サブスクリプションの名前とフィルターで、サービス名前空間のすべてのルールの列挙可能なコレクションを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>
            <a name="filter-expression-format---propery-logical-operator-value-filter-expression"></a>フィルター式の形式: {プロパティ} {論理演算子、{value} {フィルター式}}
            -----------------------------------------------------------------------------------------
            使用可能なプロパティ: ModifiedAt |AccessedAt |CreatedAt 論理演算子: Eq |Ne |Gt |Ge |Lt |Le  
            値: 対応するプロパティの型の値。
            </remarks>
        <example>
          <code>
            var fiveMinutesAgo DateTime.UtcNow.AddMinutes(-5) を = です。ToString ("M/dd/yyyy hh:mm:ss") です。var rulesInTheLast5Minutes = await namespaceManager.GetRulesAsync (topicName、subscriptionName、$"createdAt gt '{fiveMinutesAgo}'") です。
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription GetSubscription (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription GetSubscription(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscription(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscription (topicPath As String, name As String) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.GetSubscription : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.GetSubscription (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <summary>サービスの名前空間からトピックを取得します。</summary>
        <returns>A <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> 、サブスクリプションへのハンドルまたは<see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" />サービス名前空間には、サブスクリプションが存在しない場合は例外です。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">サブスクリプションは、サービス名前空間ではありません。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptionAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptionAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptionAsync (topicPath As String, name As String) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptionAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.GetSubscriptionAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <summary>非同期的に、サービス名前空間からトピックを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions (string topicPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions(string topicPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptions(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptions (topicPath As String) As IEnumerable(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptions : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.GetSubscriptions topicPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>サービス名前空間内のすべてのサブスクリプションの列挙可能なコレクションを取得します。</summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerable`1" />オブジェクトのうち、サービス名前空間内のすべてのサブスクリプションのコレクションを表しますまたはサブスクリプションが存在しない場合は、空のコレクションを返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions (string topicPath, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions(string topicPath, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptions(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptions (topicPath As String, filter As String) As IEnumerable(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptions : string * string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.GetSubscriptions (topicPath, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <param name="filter">サブスクリプションを取得するフィルター選択に使用する文字列。</param>
        <summary>指定されたトピック パスおよびフィルターでサービス名前空間内のすべてのサブスクリプションの列挙可能なコレクションを取得します。</summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerable`1" />オブジェクトのうち、サービス名前空間内のすべてのサブスクリプションのコレクションを表しますまたはサブスクリプションが存在しない場合は、空のコレクションを返します。</returns>
        <remarks>
            式の形式をフィルター処理: {プロパティ} {論理演算子、{value}} {フィルター式} と {関数} {論理演算子、{value}} {フィルター式} と
                                        -----------------------------------------------------------------------------------------
            使用可能なプロパティ: ModifiedAt |AccessedAt |CreatedAt |MessageCount 論理演算子: Eq |Ne |Gt |Ge |Lt |Le  
            値: 型関数の対応するプロパティの値: startswith ({プロパティ} {value})
            </remarks>
        <example>
          <code>
            var subscriptionsWithMessages = namespaceManager.GetSubscriptions ("topicName"、"messageCount Gt 0") です。var subscriptionsStartsWith = namespaceManager.GetSubscriptions ("topicName"、$"startswith (パス、'subscription') eq true") です。
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync (string topicPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync(string topicPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptionsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptionsAsync (topicPath As String) As Task(Of IEnumerable(Of SubscriptionDescription))" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptionsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;" Usage="namespaceManager.GetSubscriptionsAsync topicPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>非同期的に、サービス名前空間内のすべてのサブスクリプションの列挙可能なコレクションを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync (string topicPath, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync(string topicPath, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptionsAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptionsAsync (topicPath As String, filter As String) As Task(Of IEnumerable(Of SubscriptionDescription))" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptionsAsync : string * string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;" Usage="namespaceManager.GetSubscriptionsAsync (topicPath, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <param name="filter">サブスクリプションを取得するフィルター選択に使用する文字列。</param>
        <summary>非同期的に、サービス名前空間内のすべてのサブスクリプションの列挙可能なコレクションを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>
            式の形式をフィルター処理: {プロパティ} {論理演算子、{value}} {フィルター式} と {関数} {論理演算子、{value}} {フィルター式} と
                                        -----------------------------------------------------------------------------------------
            使用可能なプロパティ: ModifiedAt |AccessedAt |CreatedAt |MessageCount 論理演算子: Eq |Ne |Gt |Ge |Lt |Le  
            値: 型関数の対応するプロパティの値: startswith ({プロパティ} {value})
            </remarks>
        <example>
          <code>
            var subscriptionsWithMessages = await namespaceManager.GetSubscriptionsAsync ("topicName"、"messageCount Gt 0") です。var subscriptionsStartsWith = await namespaceManager.GetSubscriptionsAsync ("topicName"、$"startswith (パス、'subscription') eq true") です。
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription GetTopic (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription GetTopic(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopic (path As String) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.GetTopic : string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.GetTopic path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>サービスの名前空間からトピックを取得します。</summary>
        <returns>A<see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />トピックへの参照または<see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" />サービス名前空間にトピックが存在しない場合は例外です。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />空または null。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きく必要があります、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:System.UnauthorizedAccessException"><see cref="T:Microsoft.ServiceBus.NamespaceManager" />オブジェクトには、この操作を実行するための十分なアクセス許可はありません。 されることを確認する必要があります、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />が正しい<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />資格情報、操作を実行します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">サービス名前空間にトピックがありませんでした。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopicAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopicAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopicAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopicAsync (path As String) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.GetTopicAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.GetTopicAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>非同期的に、サービス名前空間からトピックを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopics" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopics () As IEnumerable(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.GetTopics : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.GetTopics " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>サービス名前空間のトピックのコレクションを取得します。</summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerable`1" />オブジェクトのうち、現在の名前空間の下にあるトピックのコレクションを表しますまたはトピックが存在しない場合は、空のコレクションを返します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">操作がタイムアウトになりました。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きく必要があります、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:System.UnauthorizedAccessException"><see cref="T:Microsoft.ServiceBus.NamespaceManager" />オブジェクトには、この操作を実行するための十分なアクセス許可はありません。 されることを確認する必要があります、<see cref="T:Microsoft.ServiceBus.NamespaceManager" />が正しい<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" />資格情報、操作を実行します。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生します。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetTopics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopics(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopics (filter As String) As IEnumerable(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.GetTopics : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.GetTopics filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">取得する項目をフィルター処理に使用する文字列。</param>
        <summary>指定されたフィルターを使用して、サービス名前空間のトピックのコレクションを取得します。 エンティティの名前 (など語句で始まる)、エンティティの長さ (Gt または長期)、作成、更新、およびアクセス時刻 (Gt または長期) の組み合わせによってフィルター処理することができます。</summary>
        <returns><see cref="T:System.Collections.Generic.IEnumerable`1" />オブジェクトのうち、現在の名前空間の下にあるトピックのコレクションを表しますまたはトピックが存在しない場合は、空のコレクションを返します。</returns>
        <remarks>
            式の形式をフィルター処理: {プロパティ} {論理演算子、{value}} {フィルター式} と {関数} {論理演算子、{value}} {フィルター式} と
                                        -----------------------------------------------------------------------------------------
            使用可能なプロパティ: パス |ModifiedAt |AccessedAt |CreatedAt |MessageCount 論理演算子: Eq |Ne |Gt |Ge |Lt |Le  
            値: 型関数の対応するプロパティの値: startswith ({プロパティ} {value})
            </remarks>
        <example>
          <code>
            var topicsWithMessages = namespaceManager.GetTopics ("messageCount Gt 0") です。var topicsStartsWith = namespaceManager.GetTopics ($"startswith (パス、'トピック') eq true") です。
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetTopicsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopicsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopicsAsync () As Task(Of IEnumerable(Of TopicDescription))" />
      <MemberSignature Language="F#" Value="member this.GetTopicsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;" Usage="namespaceManager.GetTopicsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>非同期的に、サービス名前空間のトピックのコレクションを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopicsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopicsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopicsAsync (filter As String) As Task(Of IEnumerable(Of TopicDescription))" />
      <MemberSignature Language="F#" Value="member this.GetTopicsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;" Usage="namespaceManager.GetTopicsAsync filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">取得する項目をフィルター処理に使用する文字列。</param>
        <summary>非同期的に、サービス名前空間のトピックのコレクションを取得します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>
            式の形式をフィルター処理: {プロパティ} {論理演算子、{value}} {フィルター式} と {関数} {論理演算子、{value}} {フィルター式} と
                                        -----------------------------------------------------------------------------------------
            使用可能なプロパティ: パス |ModifiedAt |AccessedAt |CreatedAt |MessageCount 論理演算子: Eq |Ne |Gt |Ge |Lt |Le  
            値: 型関数の対応するプロパティの値: startswith ({プロパティ} {value})
            </remarks>
        <example>
          <code>
            var topicsWithMessages = await namespaceManager.GetTopicsAsync ("messageCount Gt 0") です。var topicsStartsWith = await namespaceManager.GetTopicsAsync ($"startswith (パス、'トピック') eq true") です。
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfo">
      <MemberSignature Language="C#" Value="public string GetVersionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetVersionInfo() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetVersionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfo () As String" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfo : unit -&gt; string" Usage="namespaceManager.GetVersionInfo " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetVersionInfoAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfoAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfoAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="namespaceManager.GetVersionInfoAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
    <Member MemberName="ProtocolVersion">
      <MemberSignature Language="C#" Value="public const string ProtocolVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ProtocolVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.NamespaceManager.ProtocolVersion" />
      <MemberSignature Language="VB.NET" Value="Public Const ProtocolVersion As String " />
      <MemberSignature Language="F#" Value="val mutable ProtocolVersion : string" Usage="Microsoft.ServiceBus.NamespaceManager.ProtocolVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>クライアント プロトコルのバージョンを示す"YYYY MM"の形式の文字列を指定します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueExists">
      <MemberSignature Language="C#" Value="public bool QueueExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool QueueExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.QueueExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function QueueExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.QueueExists : string -&gt; bool" Usage="namespaceManager.QueueExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <summary>サービスの名前空間にキューが存在するかどうかを判断します。</summary>
        <returns>サービス名前空間にキューが存在する場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; QueueExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; QueueExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.QueueExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function QueueExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.QueueExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.QueueExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスに対して、このキューのパス。</param>
        <summary>サービスの名前空間にキューが存在するかどうかを非同期に判断します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayExists">
      <MemberSignature Language="C#" Value="public bool RelayExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool RelayExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RelayExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RelayExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.RelayExists : string -&gt; bool" Usage="namespaceManager.RelayExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">リレー サービスの名前空間のベース アドレスに対する相対パス。</param>
        <summary>サービスの名前空間にリレーが存在するかどうかを判断します。</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; RelayExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; RelayExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RelayExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RelayExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RelayExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.RelayExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceBus.NamespaceManager/&lt;RelayExistsAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">リレー サービスの名前空間のベース アドレスに対する相対パス。</param>
        <summary>サービスの名前空間にリレーが存在するかどうかを非同期に判断します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription RenameQueue (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription RenameQueue(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameQueue(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameQueue (path As String, newPath As String) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.RenameQueue : string * string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.RenameQueue (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">既存のキューへのパス。</param>
        <param name="newPath">名前が変更されたキューに新しいパス。</param>
        <summary>名前空間の内部キューの名前を変更します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">場合にスローされる<paramref name="path" />が null または空です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">場合にスローされるの長さ<paramref name="path" />以上 290 文字です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きくことができます、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">指定したパスに元のキューが存在しない場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">同じ名前空間内で同じパスにターゲット キューが存在する場合にスローされます。</exception>
        <exception cref="T:System.UnauthorizedAccessException">クライアントは、操作を実行する資格情報を持っていない場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生した場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="RenameQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; RenameQueueAsync (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; RenameQueueAsync(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameQueueAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameQueueAsync (path As String, newPath As String) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.RenameQueueAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.RenameQueueAsync (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">既存のキューへのパス。</param>
        <param name="newPath">名前が変更されたキューに新しいパス。</param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.RenameQueue(System.String,System.String)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">場合にスローされる<paramref name="path" />が null または空です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">場合にスローされるの長さ<paramref name="path" />以上 290 文字です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きくことができます、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">指定したパスに元のキューが存在しない場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">同じ名前空間内で同じパスにターゲット キューが存在する場合にスローされます。</exception>
        <exception cref="T:System.UnauthorizedAccessException">クライアントは、操作を実行する資格情報を持っていない場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生した場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="RenameTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription RenameTopic (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription RenameTopic(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameTopic(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameTopic (path As String, newPath As String) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.RenameTopic : string * string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.RenameTopic (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">既存のトピックへのパス。</param>
        <param name="newPath">名前が変更されたトピックへの新しいパス。</param>
        <summary>名前空間内のトピックの名前を変更します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">場合にスローされる<paramref name="path" />が null または空です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">場合にスローされるの長さ<paramref name="path" />以上 290 文字です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きくことができます、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">指定したパスに、転送元トピックが存在しない場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">同じ名前空間内で同じパスを持つターゲット トピックが存在する場合にスローされます。</exception>
        <exception cref="T:System.UnauthorizedAccessException">クライアントは、操作を実行する資格情報を持っていない場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生した場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="RenameTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; RenameTopicAsync (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; RenameTopicAsync(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameTopicAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameTopicAsync (path As String, newPath As String) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.RenameTopicAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.RenameTopicAsync (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">既存のトピックへのパス。</param>
        <param name="newPath">名前が変更されたトピックへの新しいパス。</param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.RenameTopic(System.String,System.String)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">場合にスローされる<paramref name="path" />が null または空です。</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">場合にスローされるの長さ<paramref name="path" />以上 290 文字です。</exception>
        <exception cref="T:System.TimeoutException">操作がタイムアウトしたときにスローされます。を介して、タイムアウト期間が初期化されて、<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />クラスです。 値を大きくことができます、<see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" />タイムアウト値が比較的少ない場合は、この例外を回避するプロパティです。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">指定したパスに、転送元トピックが存在しない場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">同じ名前空間内で同じパスを持つターゲット トピックが存在する場合にスローされます。</exception>
        <exception cref="T:System.UnauthorizedAccessException">クライアントは、操作を実行する資格情報を持っていない場合にスローされます。</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">内部エラーまたは予期しない例外が発生した場合にスローされます。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestorePublisher">
      <MemberSignature Language="C#" Value="public void RestorePublisher (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RestorePublisher(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RestorePublisher(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RestorePublisher (entityPath As String, publisher As String)" />
      <MemberSignature Language="F#" Value="member this.RestorePublisher : string * string -&gt; unit" Usage="namespaceManager.RestorePublisher (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">イベント ハブのパス、発行元が取り消されたおよび復元する必要があります。 以下を参照してください。<see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /></param>
        <param name="publisher">失効したパブリッシャーです。</param>
        <summary>Event Hubs の失効一覧からパブリッシャーを削除します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePublisherAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestorePublisherAsync (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestorePublisherAsync(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RestorePublisherAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestorePublisherAsync (entityPath As String, publisher As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RestorePublisherAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.RestorePublisherAsync (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">イベント ハブのパス、発行元が取り消されたおよび復元する必要があります。 以下を参照してください。<see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /></param>
        <param name="publisher">失効したパブリッシャーです。</param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.RestorePublisher(System.String,System.String)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokePublisher">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RevokedPublisherDescription RevokePublisher (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription RevokePublisher(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RevokePublisher(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RevokePublisher (entityPath As String, publisher As String) As RevokedPublisherDescription" />
      <MemberSignature Language="F#" Value="member this.RevokePublisher : string * string -&gt; Microsoft.ServiceBus.Messaging.RevokedPublisherDescription" Usage="namespaceManager.RevokePublisher (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RevokedPublisherDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">イベント ハブのパスがするパブリッシャーを取り消す必要があります。 以下を参照してください。<see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /></param>
        <param name="publisher">取り消すパブリッシャーです。</param>
        <summary>Event Hubs の失効リストに、パブリッシャーを追加します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.RevokedPublisherDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokePublisherAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; RevokePublisherAsync (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; RevokePublisherAsync(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RevokePublisherAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RevokePublisherAsync (entityPath As String, publisher As String) As Task(Of RevokedPublisherDescription)" />
      <MemberSignature Language="F#" Value="member this.RevokePublisherAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;" Usage="namespaceManager.RevokePublisherAsync (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">イベント ハブのパスがするパブリッシャーを取り消す必要があります。 以下を参照してください。<see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /></param>
        <param name="publisher">取り消すパブリッシャーです。</param>
        <summary><see cref="M:Microsoft.ServiceBus.NamespaceManager.RevokePublisher(System.String,System.String)" /> の非同期バージョン。</summary>
        <returns><see cref="T:System.Threading.Tasks.Task`1" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NamespaceManagerSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NamespaceManagerSettings Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NamespaceManager.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As NamespaceManagerSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : Microsoft.ServiceBus.NamespaceManagerSettings" Usage="Microsoft.ServiceBus.NamespaceManager.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManagerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>サービス名前空間のクライアント設定を取得します。</summary>
        <value>A<see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" />サービス名前空間のクライアント設定を表すオブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionExists">
      <MemberSignature Language="C#" Value="public bool SubscriptionExists (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool SubscriptionExists(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.SubscriptionExists(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubscriptionExists (topicPath As String, name As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.SubscriptionExists : string * string -&gt; bool" Usage="namespaceManager.SubscriptionExists (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <summary>サービス名前空間にサブスクリプションが存在するかどうかを判断します。</summary>
        <returns>true の場合、サブスクリプション、サービス名前空間に存在します。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; SubscriptionExistsAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; SubscriptionExistsAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.SubscriptionExistsAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubscriptionExistsAsync (topicPath As String, name As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SubscriptionExistsAsync : string * string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.SubscriptionExistsAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <param name="name">サブスクリプションの名前。</param>
        <summary>サービスの名前空間に、サブスクリプションが存在するかどうかを非同期に判断します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicExists">
      <MemberSignature Language="C#" Value="public bool TopicExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TopicExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.TopicExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function TopicExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TopicExists : string -&gt; bool" Usage="namespaceManager.TopicExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>サービス名前空間にトピックが存在するかどうかを判断します。</summary>
        <returns>サービス名前空間にトピックが存在する場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TopicExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; TopicExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.TopicExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function TopicExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.TopicExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.TopicExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">サービス名前空間のベース アドレスを基準としたトピックのパス。</param>
        <summary>サービス名前空間にトピックが存在するかどうかを非同期に判断します。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription UpdateConsumerGroup (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription UpdateConsumerGroup(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateConsumerGroup(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateConsumerGroup (description As ConsumerGroupDescription) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateConsumerGroup : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.UpdateConsumerGroup description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />更新された情報を含むオブジェクト。</param>
        <summary>イベント ハブ コンシューマー グループを更新します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; UpdateConsumerGroupAsync (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; UpdateConsumerGroupAsync(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateConsumerGroupAsync(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateConsumerGroupAsync (description As ConsumerGroupDescription) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateConsumerGroupAsync : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.UpdateConsumerGroupAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description">コンシューマー グループの説明。</param>
        <summary>コンシューマー グループを非同期に更新します。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription UpdateEventHub (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription UpdateEventHub(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateEventHub(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateEventHub (description As EventHubDescription) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateEventHub : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.UpdateEventHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description"><see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />更新された情報を含むオブジェクト。</param>
        <summary>Event Hub を更新します。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> を返します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; UpdateEventHubAsync (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; UpdateEventHubAsync(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateEventHubAsync(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateEventHubAsync (description As EventHubDescription) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateEventHubAsync : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.UpdateEventHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">イベント ハブの説明。</param>
        <summary>イベント ハブを非同期に更新します。</summary>
        <returns>非同期操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription UpdateQueue (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription UpdateQueue(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateQueue(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateQueue (description As QueueDescription) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateQueue : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.UpdateQueue description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />を更新するキューを記述するオブジェクト。</param>
        <summary>キューを更新できます。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />のキューに更新されました。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; UpdateQueueAsync (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; UpdateQueueAsync(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateQueueAsync(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateQueueAsync (description As QueueDescription) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateQueueAsync : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.UpdateQueueAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />を更新するキューを記述するオブジェクト。</param>
        <summary>非同期的に使用すると、キューを更新できます。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription UpdateRelay (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription UpdateRelay(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateRelay(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRelay (description As RelayDescription) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateRelay : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.UpdateRelay description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" />更新後のリレーを記述するオブジェクト。</param>
        <summary>Upddates リレー エンドポイント。</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; UpdateRelayAsync (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; UpdateRelayAsync(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateRelayAsync(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRelayAsync (description As RelayDescription) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateRelayAsync : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.UpdateRelayAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" />更新後のリレーを記述するオブジェクト。</param>
        <summary>非同期的に upddates リレー エンドポイント。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription UpdateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription UpdateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSubscription (description As SubscriptionDescription) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.UpdateSubscription description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />を更新するサブスクリプションを記述するオブジェクト。</param>
        <summary>サブスクリプションを更新できます。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />のサブスクリプションを更新します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; UpdateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; UpdateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSubscriptionAsync (description As SubscriptionDescription) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.UpdateSubscriptionAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" />を更新するサブスクリプションを記述するオブジェクト。</param>
        <summary>非同期的に使用すると、サブスクリプションを更新できます。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription UpdateTopic (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription UpdateTopic(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateTopic(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateTopic (description As TopicDescription) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateTopic : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.UpdateTopic description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />を更新するトピックを記述するオブジェクト。</param>
        <summary>トピックを更新できます。</summary>
        <returns><see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />のトピックが更新されました。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; UpdateTopicAsync (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; UpdateTopicAsync(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateTopicAsync(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateTopicAsync (description As TopicDescription) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateTopicAsync : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.UpdateTopicAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description">A<see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />を更新するトピックを記述するオブジェクト。</param>
        <summary>非同期的に使用すると、トピックを更新できます。</summary>
        <returns>非同期操作です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>