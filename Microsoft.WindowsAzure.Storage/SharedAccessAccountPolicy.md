<Type Name="SharedAccessAccountPolicy" FullName="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessAccountPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessAccountPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessAccountPolicy" />
  <TypeSignature Language="F#" Value="type SharedAccessAccountPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            開始時刻、有効期限、アクセス許可、署名付きサービス、署名されたリソースの種類、符号付きのプロトコルおよび共有アクセス署名の署名済みの IP アドレスを指定するアカウントの共有アクセス ポリシーを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAccountPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SharedAccessAccountPolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IPAddressOrRange">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.IPAddressOrRange IPAddressOrRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.IPAddressOrRange IPAddressOrRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.IPAddressOrRange" />
      <MemberSignature Language="VB.NET" Value="Public Property IPAddressOrRange As IPAddressOrRange" />
      <MemberSignature Language="F#" Value="member this.IPAddressOrRange : Microsoft.WindowsAzure.Storage.IPAddressOrRange with get, set" Usage="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.IPAddressOrRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.IPAddressOrRange</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または使用できる IP アドレスまたはこの共有アクセス ポリシーに関連付けられている共有アクセス署名の IP アドレスの範囲を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As SharedAccessAccountPermissions" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions with get, set" Usage="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この共有アクセス ポリシーに関連付けられている共有アクセス署名のアクセス許可を設定します。
            </summary>
        <value><see cref="T:Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsToString">
      <MemberSignature Language="C#" Value="public static string PermissionsToString (Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string PermissionsToString(valuetype Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.PermissionsToString(Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsToString (permissions As SharedAccessAccountPermissions) As String" />
      <MemberSignature Language="F#" Value="static member PermissionsToString : Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions -&gt; string" Usage="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.PermissionsToString permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><see cref="T:Microsoft.WindowsAzure.Storage.SharedAccessAccountPermissions" /> オブジェクト。</param>
        <summary>
            文字列に、共有アクセス ポリシーの指定されたアクセス許可に変換します。
            </summary>
        <returns>文字列の形式で共有アクセス許可。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocols">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; Protocols { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; Protocols" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.Protocols" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocols As Nullable(Of SharedAccessProtocol)" />
      <MemberSignature Language="F#" Value="member this.Protocols : Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.Protocols" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.WindowsAzure.Storage.SharedAccessProtocol&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この共有アクセス ポリシーに関連付けられている共有アクセス署名の許可されるプロトコルを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceTypes">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.SharedAccessAccountResourceTypes ResourceTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.SharedAccessAccountResourceTypes ResourceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.ResourceTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceTypes As SharedAccessAccountResourceTypes" />
      <MemberSignature Language="F#" Value="member this.ResourceTypes : Microsoft.WindowsAzure.Storage.SharedAccessAccountResourceTypes with get, set" Usage="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.ResourceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.SharedAccessAccountResourceTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この共有アクセス ポリシーに関連付けられている共有アクセス署名のリソースの種類を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceTypesToString">
      <MemberSignature Language="C#" Value="public static string ResourceTypesToString (Microsoft.WindowsAzure.Storage.SharedAccessAccountResourceTypes resourceTypes);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string ResourceTypesToString(valuetype Microsoft.WindowsAzure.Storage.SharedAccessAccountResourceTypes resourceTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.ResourceTypesToString(Microsoft.WindowsAzure.Storage.SharedAccessAccountResourceTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ResourceTypesToString (resourceTypes As SharedAccessAccountResourceTypes) As String" />
      <MemberSignature Language="F#" Value="static member ResourceTypesToString : Microsoft.WindowsAzure.Storage.SharedAccessAccountResourceTypes -&gt; string" Usage="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.ResourceTypesToString resourceTypes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceTypes" Type="Microsoft.WindowsAzure.Storage.SharedAccessAccountResourceTypes" />
      </Parameters>
      <Docs>
        <param name="resourceTypes"><see cref="T:Microsoft.WindowsAzure.Storage.SharedAccessAccountResourceTypes" /> オブジェクト。</param>
        <summary>
            文字列への共有アクセス ポリシーに指定されたリソースの種類に変換します。
            </summary>
        <returns>文字列の形式で共有アクセス リソースの種類。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Services">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.SharedAccessAccountServices Services { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.SharedAccessAccountServices Services" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.Services" />
      <MemberSignature Language="VB.NET" Value="Public Property Services As SharedAccessAccountServices" />
      <MemberSignature Language="F#" Value="member this.Services : Microsoft.WindowsAzure.Storage.SharedAccessAccountServices with get, set" Usage="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.Services" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.SharedAccessAccountServices</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この共有アクセス ポリシーに関連付けられている共有アクセス署名のサービス (blob、ファイル、キュー、テーブル) を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicesToString">
      <MemberSignature Language="C#" Value="public static string ServicesToString (Microsoft.WindowsAzure.Storage.SharedAccessAccountServices services);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string ServicesToString(valuetype Microsoft.WindowsAzure.Storage.SharedAccessAccountServices services) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.ServicesToString(Microsoft.WindowsAzure.Storage.SharedAccessAccountServices)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ServicesToString (services As SharedAccessAccountServices) As String" />
      <MemberSignature Language="F#" Value="static member ServicesToString : Microsoft.WindowsAzure.Storage.SharedAccessAccountServices -&gt; string" Usage="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.ServicesToString services" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="services" Type="Microsoft.WindowsAzure.Storage.SharedAccessAccountServices" />
      </Parameters>
      <Docs>
        <param name="services"><see cref="T:Microsoft.WindowsAzure.Storage.SharedAccessAccountServices" /> オブジェクト。</param>
        <summary>
            文字列に、共有アクセス ポリシーの指定されたサービスに変換します。
            </summary>
        <returns>文字列の形式で共有アクセス サービス。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.SharedAccessExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessExpiryTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessExpiryTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.SharedAccessExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この共有アクセス ポリシーに関連付けられている共有アクセス署名の有効期限を設定します。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />共有アクセスの有効期限を指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.SharedAccessStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessStartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessStartTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.SharedAccessAccountPolicy.SharedAccessStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この共有アクセス ポリシーに関連付けられている共有アクセス署名の開始時刻を設定します。
            </summary>
        <value>A<see cref="T:System.DateTimeOffset" />開始時刻を共有のアクセスを指定します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>