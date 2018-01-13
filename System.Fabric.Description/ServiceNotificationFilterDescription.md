<Type Name="ServiceNotificationFilterDescription" FullName="System.Fabric.Description.ServiceNotificationFilterDescription">
  <TypeSignature Language="C#" Value="public class ServiceNotificationFilterDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceNotificationFilterDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServiceNotificationFilterDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceNotificationFilterDescription" />
  <TypeSignature Language="F#" Value="type ServiceNotificationFilterDescription = class" />
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
      <para>によって登録されたサービスの通知の配信用のフィルターの記述に使用されるクラスを表します<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceNotificationFilterDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceNotificationFilterDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceNotificationFilterDescription (Uri name, bool matchNamePrefix, bool matchPrimaryChangeOnly);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri name, bool matchNamePrefix, bool matchPrimaryChangeOnly) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ServiceNotificationFilterDescription.#ctor(System.Uri,System.Boolean,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As Uri, matchNamePrefix As Boolean, matchPrimaryChangeOnly As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ServiceNotificationFilterDescription : Uri * bool * bool -&gt; System.Fabric.Description.ServiceNotificationFilterDescription" Usage="new System.Fabric.Description.ServiceNotificationFilterDescription (name, matchNamePrefix, matchPrimaryChangeOnly)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="matchNamePrefix" Type="System.Boolean" />
        <Parameter Name="matchPrimaryChangeOnly" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>通知の配信サービスの名前です。</para>
        </param>
        <param name="matchNamePrefix">
          <para>すべての service 通知名は、プレフィックスかどうかを示すフラグが配信されます。</para>
        </param>
        <param name="matchPrimaryChangeOnly">
          <para>プライマリ レプリカのエンドポイントが変更されていない通知をフィルターしてサービス通知の配信に一致するかどうかを示すフラグです。 このフラグには、ステートレスなサービスの効果はありません。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MatchNamePrefix">
      <MemberSignature Language="C#" Value="public bool MatchNamePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MatchNamePrefix" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.MatchNamePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property MatchNamePrefix As Boolean" />
      <MemberSignature Language="F#" Value="member this.MatchNamePrefix : bool with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.MatchNamePrefix" />
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
          <para>名前のプレフィックスすべてのサービスの通知を配信するかどうかを示す値を取得します。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>名のプレフィックスすべてのサービス通知は配信された、それ以外になる場合<languageKeyword>false</languageKeyword>です。 既定値は <languageKeyword>false</languageKeyword> です。</para>
        </value>
        <remarks>
            文字列プレフィックスではなく、URI セグメントのプレフィックスの一致項目がサービス名と一致するので、プレフィックスの一致が発生します。 名前のフィルター"ファブリック:/abc"という名前の一致するサービスをプレフィックス"ファブリック:/abc"と"fabric:/abc def"、という名前のサービスされませんが、"ファブリック:/abc_def"です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MatchPrimaryChangeOnly">
      <MemberSignature Language="C#" Value="public bool MatchPrimaryChangeOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool MatchPrimaryChangeOnly" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.MatchPrimaryChangeOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property MatchPrimaryChangeOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.MatchPrimaryChangeOnly : bool with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.MatchPrimaryChangeOnly" />
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
          <para>プライマリ レプリカのエンドポイントが変更されていない通知をフィルターしてサービス通知の配信に一致するかどうかを示す値を取得します。 このフラグには、ステートレスなサービスの効果はありません。</para>
        </summary>
        <value>
          <para>
            <languageKeyword>true</languageKeyword>のみです。 それ以外の場合には、主な変更をと一致するフィルター場合<languageKeyword>false</languageKeyword>です。 既定値は <languageKeyword>false</languageKeyword> です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Uri Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ServiceNotificationFilterDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As Uri" />
      <MemberSignature Language="F#" Value="member this.Name : Uri with get, set" Usage="System.Fabric.Description.ServiceNotificationFilterDescription.Name" />
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
          <para>通知の配信サービスの名前を取得します。 名前は、ファブリックにする必要があります。 スキームです。 ルートの名前 ("fabric:") は許可されています。</para>
        </summary>
        <value>
          <para>通知の配信サービスの名前です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>