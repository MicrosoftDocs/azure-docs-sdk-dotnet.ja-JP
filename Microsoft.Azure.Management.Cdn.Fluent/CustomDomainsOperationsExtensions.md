<Type Name="CustomDomainsOperationsExtensions" FullName="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CustomDomainsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CustomDomainsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CustomDomainsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CustomDomainsOperationsExtensions = class" />
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
            CustomDomainsOperations の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginCreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginCreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;BeginCreateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
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
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="customDomainName">
            エンドポイント内でカスタム ドメインの名前です。
            </param>
        <param name="hostName">
            カスタム ドメインのホスト名。 ドメイン名である必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            エンドポイント内の新しいカスタム ドメインを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
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
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="customDomainName">
            エンドポイント内でカスタム ドメインの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            エンドポイント内の既存のカスタム ドメインを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; CreateAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; CreateAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.CreateAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;CreateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
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
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="customDomainName">
            エンドポイント内でカスタム ドメインの名前です。
            </param>
        <param name="hostName">
            カスタム ドメインのホスト名。 ドメイン名である必要があります。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            エンドポイント内の新しいカスタム ドメインを作成します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DeleteAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DeleteAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
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
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="customDomainName">
            エンドポイント内でカスタム ドメインの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            エンドポイント内の既存のカスタム ドメインを削除します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableCustomHttpsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DisableCustomHttpsAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; DisableCustomHttpsAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DisableCustomHttpsAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableCustomHttpsAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.DisableCustomHttpsAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;DisableCustomHttpsAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
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
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="customDomainName">
            エンドポイント内でカスタム ドメインの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            カスタム ドメインの https 配信を無効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableCustomHttpsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; EnableCustomHttpsAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; EnableCustomHttpsAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.EnableCustomHttpsAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableCustomHttpsAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.EnableCustomHttpsAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;EnableCustomHttpsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
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
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="customDomainName">
            エンドポイント内でカスタム ドメインの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            カスタム ドメインの https 配信を有効にします。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; GetAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt; GetAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, string customDomainName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, endpointName, customDomainName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="customDomainName" Type="System.String" />
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
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="customDomainName">
            エンドポイント内でカスタム ドメインの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            エンドポイント内の既存のカスタム ドメインを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string resourceGroupName, string profileName, string endpointName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointAsync (operations, resourceGroupName, profileName, endpointName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;ListByEndpointAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="endpointName" Type="System.String" />
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
        <param name="endpointName">
            グローバルに一意なプロファイルに基づいて、エンドポイントの名前です。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            すべてのエンドポイント内の既存のカスタム ドメインの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByEndpointNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointNextAsync (this Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt; ListByEndpointNextAsync(class Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointNextAsync(Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByEndpointNextAsync : Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions.ListByEndpointNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Cdn.Fluent.CustomDomainsOperationsExtensions/&lt;ListByEndpointNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.CustomDomainInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Cdn.Fluent.ICustomDomainsOperations" RefType="this" />
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
            すべてのエンドポイント内の既存のカスタム ドメインの一覧を表示します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>