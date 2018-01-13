<Type Name="SharedAccessTablePolicy" FullName="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessTablePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessTablePolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessTablePolicy" />
  <TypeSignature Language="F#" Value="type SharedAccessTablePolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            開始時刻、有効期限、および共有アクセス署名のアクセス許可を指定する共有アクセス ポリシーを表します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessTablePolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            SharedAccessTablePolicy クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Permissions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions Permissions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions Permissions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.Permissions" />
      <MemberSignature Language="VB.NET" Value="Public Property Permissions As SharedAccessTablePermissions" />
      <MemberSignature Language="F#" Value="member this.Permissions : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions with get, set" Usage="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.Permissions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、この共有アクセス ポリシーに関連付けられている共有アクセス署名のアクセス許可を設定します。
            </summary>
        <value><see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" /> オブジェクト。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsFromString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions PermissionsFromString (string input);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig valuetype Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions PermissionsFromString(string input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.PermissionsFromString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsFromString (input As String) As SharedAccessTablePermissions" />
      <MemberSignature Language="F#" Value="static member PermissionsFromString : string -&gt; Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" Usage="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.PermissionsFromString input" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="input" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="input">文字列の形式で共有アクセス許可。</param>
        <summary>
            構築、<see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" />アクセス許可文字列からオブジェクト。
            </summary>
        <returns><see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" /> オブジェクト。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionsToString">
      <MemberSignature Language="C#" Value="public static string PermissionsToString (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string PermissionsToString(valuetype Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.PermissionsToString(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PermissionsToString (permissions As SharedAccessTablePermissions) As String" />
      <MemberSignature Language="F#" Value="static member PermissionsToString : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions -&gt; string" Usage="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.PermissionsToString permissions" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions"><see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePermissions" /> オブジェクト。</param>
        <summary>
            文字列に、共有アクセス ポリシーの指定されたアクセス許可に変換します。
            </summary>
        <returns>文字列の形式で共有アクセス許可。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SharedAccessExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SharedAccessExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.SharedAccessExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessExpiryTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessExpiryTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.SharedAccessExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.SharedAccessStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessStartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SharedAccessStartTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy.SharedAccessStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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