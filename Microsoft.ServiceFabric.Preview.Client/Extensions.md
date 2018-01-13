<Type Name="Extensions" FullName="Microsoft.ServiceFabric.Preview.Client.Extensions">
  <TypeSignature Language="C#" Value="public static class Extensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit Extensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Extensions" />
  <TypeSignature Language="VB.NET" Value="Public Module Extensions" />
  <TypeSignature Language="F#" Value="type Extensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            FabricClient の拡張メソッド。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription)" />
      <MemberSignature Language="F#" Value="static member CreateComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync (client, composeDeploymentDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="composeDeploymentDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" /> オブジェクト。</param>
        <param name="composeDeploymentDescription">
          <para><see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />作成する展開を作成するをについて説明します。</para>
        </param>
        <summary>
          <para>作成し、作成する展開の説明が説明されている Service Fabric compose 展開をインスタンス化します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />要求されたアプリケーションの種類用にプロビジョニングされたマニフェストに対して作成するアプリケーションの要求が正しくありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: 破損したファイルは、イメージ ストアに見つかりました。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: 作成する展開が既に作成されました。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: アプリケーションは既に作成されて配置を構成するようにを作成できません。 同じ名前を使用します。 </para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>イメージ ストア上のファイルへのアクセス エラーが発生しました。</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>必要なファイルが見つかりませんでした。</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                使用して指定されたパラメーター、<see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />が正しくありません。
              </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="static member CreateComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync (client, composeDeploymentDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="composeDeploymentDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" /> オブジェクト。</param>
        <param name="composeDeploymentDescription">
          <para><see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />作成する展開を作成するをについて説明します。</para>
        </param>
        <param name="timeout">
          <para>時刻を返す前に続行するには、この操作により、システムの最大量を定義<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <summary>
          <para>作成し、作成する展開の説明が説明されている Service Fabric compose 展開をインスタンス化します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />要求されたアプリケーションの種類用にプロビジョニングされたマニフェストに対して作成するアプリケーションの要求が正しくありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: 破損したファイルは、イメージ ストアに見つかりました。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: 作成する展開が既に作成されました。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: アプリケーションは既に作成されて配置を構成するようにを作成できません。 同じ名前を使用します。 </para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>イメージ ストア上のファイルへのアクセス エラーが発生しました。</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>必要なファイルが、イメージ ストアに見つかりませんでした。</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>イメージ ストアに必要なディレクトリが見つかりませんでした。</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                使用して指定されたパラメーター、<see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />が正しくありません。
              </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync (client, composeDeploymentDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="composeDeploymentDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" /> オブジェクト。</param>
        <param name="composeDeploymentDescription">
          <para><see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />作成する展開を作成するをについて説明します。</para>
        </param>
        <param name="timeout">
          <para>時刻を返す前に続行するには、この操作により、システムの最大量を定義<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>この CancellationToken は、操作を確認します。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>作成し、作成する展開の説明が説明されている Service Fabric compose 展開をインスタンス化します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />要求されたアプリケーションの種類用にプロビジョニングされたマニフェストに対して作成するアプリケーションの要求が正しくありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />アプリケーション名は、有効な名前付けの URI ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: 破損したファイルは、イメージ ストアに見つかりました。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: 作成する展開が既に作成されました。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: アプリケーションは既に作成されて配置を構成するようにを作成できません。 同じ名前を使用します。 </para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>イメージ ストア上のファイルへのアクセス エラーが発生しました。</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>必要なファイルが、イメージ ストアに見つかりませんでした。</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>イメージ ストアに必要なディレクトリが見つかりませんでした。</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>イメージ ストアのファイルまたはディレクトリへのパスが長すぎます。</para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: エラーがありました IO イメージ ストアと通信します。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                使用して指定されたパラメーター、<see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />が正しくありません。
              </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteComposeDeploymentAsync (client As FabricClient.ComposeDeploymentClient, description As DeleteComposeDeploymentDescription) As Task" />
      <MemberSignature Language="F#" Value="static member DeleteComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync (client, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="description" Type="Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" /> オブジェクト。</param>
        <param name="description">
          <para><see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />展開を作成するかを決定する、削除しないでください。</para>
        </param>
        <summary>
          <para>クラスターから作成する配置のインスタンスを削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>すべて作成する展開の状態は失われ、作成する展開を削除した後に回復できません。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: 作成する展開が存在しません。
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。 </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteComposeDeploymentAsync (client As FabricClient.ComposeDeploymentClient, description As DeleteComposeDeploymentDescription, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="static member DeleteComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync (client, description, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="description" Type="Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" /> オブジェクト。</param>
        <param name="description">
          <para><see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />展開を作成するかを決定する、削除しないでください。</para>
        </param>
        <param name="timeout">
          <para>System.TimeoutException を返す前に続行するには、この操作により、システム時刻の最大量を定義します。</para>
        </param>
        <summary>
          <para>クラスターから作成する展開を削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>すべてのアプリケーションの状態は失われ、アプリケーションを削除した後に回復できません。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: 作成する展開が存在しません。
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。 </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync (client, description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="description" Type="Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" /> オブジェクト。</param>
        <param name="description">
          <para><see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />展開を作成するかを決定する、削除しないでください。</para>
        </param>
        <param name="timeout">
          <para>System.TimeoutException を返す前に続行するには、この操作により、システム時刻の最大量を定義します。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>クラスターから作成する展開を削除します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />操作を表すです。</para>
        </returns>
        <remarks>
          <para>すべてのアプリケーションの状態は失われ、アプリケーションを削除した後に回復できません。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: 作成する展開が存在しません。
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: アプリケーションをアップグレード中です。 </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentStatusPagedListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync (this System.Fabric.FabricClient.QueryClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync(class System.Fabric.FabricClient/QueryClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync(System.Fabric.FabricClient.QueryClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetComposeDeploymentStatusPagedListAsync (client As FabricClient.QueryClient, composeDeploymentQueryDescription As ComposeDeploymentStatusQueryDescription) As Task(Of ComposeDeploymentStatusList)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentStatusPagedListAsync : System.Fabric.FabricClient.QueryClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync (client, composeDeploymentQueryDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+QueryClient" RefType="this" />
        <Parameter Name="composeDeploymentQueryDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" /> オブジェクト。</param>
        <param name="composeDeploymentQueryDescription">
          <para><see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />の展開を作成するかを決定するクエリを実行する必要があります。</para>
        </param>
        <summary>
          <para>状態 (存在する場合)、クエリの説明で指定されたフィルターに一致するように作成した展開の構成を取得します。
            作成する展開は、ページに収まり切らない、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。
            TResult のパラメーターの値は、<see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" />の一覧を表す内のフィルターを適用する展開を作成、<see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />ページに合わせてとします。
            展開の構成に一致する、指定されたクエリの説明を持たない、これはエントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentStatusPagedListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync (this System.Fabric.FabricClient.QueryClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync(class System.Fabric.FabricClient/QueryClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync(System.Fabric.FabricClient.QueryClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetComposeDeploymentStatusPagedListAsync (client As FabricClient.QueryClient, composeDeploymentQueryDescription As ComposeDeploymentStatusQueryDescription, timeout As TimeSpan) As Task(Of ComposeDeploymentStatusList)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentStatusPagedListAsync : System.Fabric.FabricClient.QueryClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync (client, composeDeploymentQueryDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+QueryClient" RefType="this" />
        <Parameter Name="composeDeploymentQueryDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" /> オブジェクト。</param>
        <param name="composeDeploymentQueryDescription">
          <para><see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />の展開を作成するかを決定するクエリを実行する必要があります。</para>
        </param>
        <param name="timeout">
          <para>時刻を返す前に続行するには、この操作により、システムの最大量を定義<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <summary>
          <para>状態 (存在する場合)、クエリの説明で指定されたフィルターに一致するように作成した展開の構成を取得します。
            作成する展開は、ページに収まり切らない、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。
            TResult のパラメーターの値は、<see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" />の一覧を表す内のフィルターを適用する展開を作成、<see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />ページに合わせてとします。
            展開の構成に一致する、指定されたクエリの説明を持たない、これはエントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentStatusPagedListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync (this System.Fabric.FabricClient.QueryClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync(class System.Fabric.FabricClient/QueryClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync(System.Fabric.FabricClient.QueryClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentStatusPagedListAsync : System.Fabric.FabricClient.QueryClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync (client, composeDeploymentQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+QueryClient" RefType="this" />
        <Parameter Name="composeDeploymentQueryDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" /> オブジェクト。</param>
        <param name="composeDeploymentQueryDescription">
          <para><see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />の展開を作成するかを決定するクエリを実行する必要があります。</para>
        </param>
        <param name="timeout">
          <para>時刻を返す前に続行するには、この操作により、システムの最大量を定義<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>この CancellationToken は、操作を確認します。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>状態 (存在する場合)、クエリの説明で指定されたフィルターに一致するように作成した展開の構成を取得します。
            作成する展開は、ページに収まり切らない、次のページを取得するために使用する継続トークンだけでなく結果の 1 つのページが返されます。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期クエリ操作を表すです。
            TResult のパラメーターの値は、<see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" />の一覧を表す内のフィルターを適用する展開を作成、<see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />ページに合わせてとします。
            展開の構成に一致する、指定されたクエリの説明を持たない、これはエントリ数が 0 の一覧を返します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                関連項目<see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.ComposeDeploymentUpgradeProgress&gt; GetComposeDeploymentUpgradeProgressAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, string deploymentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.ComposeDeploymentUpgradeProgress&gt; GetComposeDeploymentUpgradeProgressAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, string deploymentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentUpgradeProgressAsync(System.Fabric.FabricClient.ComposeDeploymentClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetComposeDeploymentUpgradeProgressAsync (client As FabricClient.ComposeDeploymentClient, deploymentName As String) As Task(Of ComposeDeploymentUpgradeProgress)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentUpgradeProgressAsync : System.Fabric.FabricClient.ComposeDeploymentClient * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ComposeDeploymentUpgradeProgress&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentUpgradeProgressAsync (client, deploymentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ComposeDeploymentUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="deploymentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" /> オブジェクト。</param>
        <param name="deploymentName">
          <para>デプロイの名前。</para>
        </param>
        <summary>
          <para>アップグレードの取得の指定された進行状況は、展開を作成します。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />結果は、指定したアップグレードの進行状況は、展開を作成します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: 作成する展開が存在しません。
            </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpgradeComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpgradeComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpgradeComposeDeploymentAsync (client As FabricClient.ComposeDeploymentClient, upgradeDescription As ComposeDeploymentUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="static member UpgradeComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync (client, upgradeDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="upgradeDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <param name="upgradeDescription">To be added.</param>
        <summary>
          <para>クラスターで、デプロイ名で識別される、作成する展開のアップグレードを開始します。</para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpgradeComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpgradeComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpgradeComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync (client, upgradeDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="upgradeDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <param name="upgradeDescription">To be added.</param>
        <param name="timeout">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
          <para>クラスターで、デプロイ名で識別される、作成する展開のアップグレードを開始します。</para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>