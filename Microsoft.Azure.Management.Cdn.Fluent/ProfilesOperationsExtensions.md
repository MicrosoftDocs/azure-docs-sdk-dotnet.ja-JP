<Type Name="ProfilesOperationsExtensions" FullName="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProfilesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProfilesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProfilesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProfilesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ProfilesOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner profile, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner profile, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, profileName, profile, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;BeginCreateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="profile" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="profile">
            プロファイルのプロパティは、新しいプロファイルの作成に必要です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したサブスクリプションとリソース グループのプロファイル名を新しい CDN プロファイルを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたパラメーターで既存の CDN プロファイルを削除します。 すべての下位のリソースの削除と、プロファイルを削除するエンドポイント、元のドメインとカスタム ドメインを含むです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, profileName, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;BeginUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="tags">
            プロファイルのタグ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したサブスクリプションとリソース グループに属する指定されたプロファイル名では、既存の CDN プロファイルを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt; CreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner profile, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt; CreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner profile, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * string * Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.CreateAsync (operations, resourceGroupName, profileName, profile, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="profile" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="profile">
            プロファイルのプロパティは、新しいプロファイルの作成に必要です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したサブスクリプションとリソース グループのプロファイル名を新しい CDN プロファイルを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定されたパラメーターで既存の CDN プロファイルを削除します。 すべての下位のリソースの削除と、プロファイルを削除するエンドポイント、元のドメインとカスタム ドメインを含むです。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateSsoUriAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.SsoUriInner&gt; GenerateSsoUriAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.SsoUriInner&gt; GenerateSsoUriAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.GenerateSsoUriAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateSsoUriAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.SsoUriInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.GenerateSsoUriAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;GenerateSsoUriAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.SsoUriInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            SSO の URI、CDN 補助ポータルにサインインするために使用する動的なを生成します。
            まだ標準プロファイル内の中核となるレポートなど、Azure ポータルで利用できない高度な機能を構成する Supplemnetal ポータルを使用します。高度な HTTP レポート、およびリアルタイムの統計およびプレミアム プロファイルのアラート、ルール エンジン。 SSO の URI は、約 10 分間隔を変更します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt; GetAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt; GetAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したサブスクリプションとリソース グループに属する指定されたプロファイル名を持つ CDN プロファイルを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての Azure サブスクリプション内で CDN プロファイルを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべてのリソース グループ内の CDN プロファイルを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべてのリソース グループ内の CDN プロファイルを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべての Azure サブスクリプション内で CDN プロファイルを一覧表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListResourceUsageAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourceUsageAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListResourceUsageAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;ListResourceUsageAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            クォータと指定された CDN プロファイルでエンドポイントの実際の使用状況を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsageNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt; ListResourceUsageNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListResourceUsageNextAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListResourceUsageNextAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.ListResourceUsageNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;ListResourceUsageNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsageInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="nextPageLink">
            一覧表示操作に成功した呼び出しからの NextLink です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            クォータと指定された CDN プロファイルでエンドポイントの実際の使用状況を確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt; UpdateAsync (this Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, System.Collections.Generic.IDictionary&lt;string,string&gt; tags, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt; UpdateAsync(class Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.ProfilesOperationsExtensions/&lt;UpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ProfileInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Azure サブスクリプション内のリソース グループの名前です。
            </param>
        <param name="profileName">
            リソース グループ内で一意である CDN プロファイルの名前です。
            </param>
        <param name="tags">
            プロファイルのタグ
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            指定したサブスクリプションとリソース グループに属する指定されたプロファイル名では、既存の CDN プロファイルを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>