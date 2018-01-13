<Type Name="ProfilesOperationsExtensions" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProfilesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProfilesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProfilesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProfilesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
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
    <Member MemberName="CheckTrafficManagerRelativeDnsNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner&gt; CheckTrafficManagerRelativeDnsNameAvailabilityAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string name = null, string type = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner&gt; CheckTrafficManagerRelativeDnsNameAvailabilityAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string name, string type, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.CheckTrafficManagerRelativeDnsNameAvailabilityAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckTrafficManagerRelativeDnsNameAvailabilityAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.CheckTrafficManagerRelativeDnsNameAvailabilityAsync (operations, name, type, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions/&lt;CheckTrafficManagerRelativeDnsNameAvailabilityAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.TrafficManagerNameAvailabilityInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="name">
            取得またはリソースの名前を設定します。
            </param>
        <param name="type">
            取得またはリソースの種類を設定します。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Traffic Manager の相対 DNS 名を使用できるかどうかを確認します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, profileName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Traffic Manager プロファイルを含む、リソース グループの名前。
            </param>
        <param name="profileName">
            Traffic Manager プロファイルの名前。
            </param>
        <param name="parameters">
            CreateOrUpdate 操作に指定された Traffic Manager プロファイルのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            作成または Traffic Manager プロファイルを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt; DeleteAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt; DeleteAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.DeleteAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.DeleteOperationResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="profileName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt; GetAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt; GetAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.GetAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.GetAsync (operations, resourceGroupName, profileName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Traffic Manager プロファイルを含む、リソース グループの名前。
            </param>
        <param name="profileName">
            Traffic Manager プロファイルの名前。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Traffic Manager プロファイルを取得します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;&gt; ListBySubscriptionAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;&gt; ListBySubscriptionAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.ListBySubscriptionAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.ListBySubscriptionAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions/&lt;ListBySubscriptionAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt; UpdateAsync (this Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt; UpdateAsync(class Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations operations, string resourceGroupName, string profileName, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations,System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions.UpdateAsync (operations, resourceGroupName, profileName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.Fluent.ProfilesOperationsExtensions/&lt;UpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.Fluent.IProfilesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="profileName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            この拡張メソッドの操作のグループです。
            </param>
        <param name="resourceGroupName">
            Traffic Manager プロファイルを含む、リソース グループの名前。
            </param>
        <param name="profileName">
            Traffic Manager プロファイルの名前。
            </param>
        <param name="parameters">
            更新操作に指定された Traffic Manager プロファイルのパラメーターです。
            </param>
        <param name="cancellationToken">
            キャンセル トークン。
            </param>
        <summary>
            Traffic Manager プロファイルを更新します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>