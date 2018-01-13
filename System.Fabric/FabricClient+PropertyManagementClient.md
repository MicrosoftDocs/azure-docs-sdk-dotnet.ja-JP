<Type Name="FabricClient+PropertyManagementClient" FullName="System.Fabric.FabricClient+PropertyManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.PropertyManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/PropertyManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.PropertyManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.PropertyManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.PropertyManagementClient = class" />
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
      <para>名前およびプロパティの管理を実行するために使用するプロパティの管理クライアントを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateNameAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateNameAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.CreateNameAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNameAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateNameAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.CreateNameAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Service Fabric 名前です。</para>
        </param>
        <summary>
          <para>指定した Service Fabric 名前を作成します。</para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を作成します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" />サービス ファブリック名は既に存在する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateNameAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateNameAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.CreateNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.CreateNameAsync (name, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Service Fabric 名前です。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定した Service Fabric 名前を作成します。</para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を作成します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" />サービス ファブリック名は既に存在する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNameAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNameAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeleteNameAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteNameAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteNameAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeleteNameAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Service Fabric 名前です。</para>
        </param>
        <summary>
          <para>指定したサービス ファブリック名を削除します。</para>
        </summary>
        <returns>
          <para>非同期の削除操作を表すタスク。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" />ときに返される<paramref name="name" />が他の名前、プロパティまたはサービスの親であります。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNameAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNameAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeleteNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeleteNameAsync (name, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Service Fabric 名前です。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定したサービス ファブリック名を削除します。</para>
        </summary>
        <returns>
          <para>非同期の削除操作を表すタスク。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" />ときに返される<paramref name="name" />が他の名前、プロパティまたはサービスの親であります。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeletePropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePropertyAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePropertyAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeletePropertyAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeletePropertyAsync (parentName As Uri, propertyName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeletePropertyAsync : Uri * string -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeletePropertyAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>プロパティの親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <summary>
          <para>指定した Service Fabric プロパティを削除します。</para>
        </summary>
        <returns>
          <para>非同期の削除操作を表すタスク。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeletePropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePropertyAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePropertyAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeletePropertyAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeletePropertyAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeletePropertyAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>URI では、プロパティの親サービス ファブリック名を定義します。</para>
        </param>
        <param name="propertyName">
          <para>文字列は、Service Fabric プロパティの名前を定義します。</para>
        </param>
        <param name="timeout">
          <para>
            <see cref="T:System.TimeSpan" />時刻を返す前に続行するには、この操作により、システムの最大量を定義<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>
            <see cref="T:System.Threading.CancellationToken" />操作を確認します。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定した Service Fabric プロパティを削除します。</para>
        </summary>
        <returns>
          <para>非同期の削除操作を表すタスク。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumeratePropertiesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync (Uri name, bool includeValues, System.Fabric.PropertyEnumerationResult previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync(class System.Uri name, bool includeValues, class System.Fabric.PropertyEnumerationResult previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumeratePropertiesAsync (name As Uri, includeValues As Boolean, previousResult As PropertyEnumerationResult) As Task(Of PropertyEnumerationResult)" />
      <MemberSignature Language="F#" Value="member this.EnumeratePropertiesAsync : Uri * bool * System.Fabric.PropertyEnumerationResult -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;" Usage="propertyManagementClient.EnumeratePropertiesAsync (name, includeValues, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="includeValues" Type="System.Boolean" />
        <Parameter Name="previousResult" Type="System.Fabric.PropertyEnumerationResult" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="includeValues">
          <para>
            <languageKeyword>True</languageKeyword>場合は、メタデータを持つ値が返されます。 <languageKeyword>False</languageKeyword> ; プロパティ メタデータのみを返す<languageKeyword>true</languageKeyword>プロパティのメタデータと値を返します。</para>
        </param>
        <param name="previousResult">
          <para>前の呼び出しのバッチの結果。 かどうか、このフィールドの最初の呼び出し必要があります設定を null にします。</para>
        </param>
        <summary>
          <para>指定した名前の下にあるすべての Service Fabric プロパティを列挙します。 </para>
        </summary>
        <returns>
          <para>非同期の get 操作を表すタスク。</para>
          <para>場合<see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" />が true の場合、この結果は次の入力として使用できます<see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" />呼び出します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>    
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumeratePropertiesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync (Uri name, bool includeValues, System.Fabric.PropertyEnumerationResult previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync(class System.Uri name, bool includeValues, class System.Fabric.PropertyEnumerationResult previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnumeratePropertiesAsync : Uri * bool * System.Fabric.PropertyEnumerationResult * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;" Usage="propertyManagementClient.EnumeratePropertiesAsync (name, includeValues, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="includeValues" Type="System.Boolean" />
        <Parameter Name="previousResult" Type="System.Fabric.PropertyEnumerationResult" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="includeValues">
          <para>
            <languageKeyword>True</languageKeyword>場合は、メタデータ、値が返されます。
                <languageKeyword>False</languageKeyword> ; プロパティ メタデータのみを返す戻り値のプロパティのメタデータと値の場合は true です。</para>
        </param>
        <param name="previousResult">
          <para>前の呼び出しのバッチの結果。 かどうか、このフィールドの最初の呼び出し必要があります設定を null にします。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定した名前の下にあるすべての Service Fabric プロパティを列挙します。</para>
        </summary>
        <returns>
          <para>非同期の get 操作を表すタスク。</para>
          <para>場合<see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" />が true の場合、この結果は次の入力として使用できます<see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" />呼び出します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>    
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumerateSubNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync (Uri name, System.Fabric.NameEnumerationResult previousResult, bool recursive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync(class System.Uri name, class System.Fabric.NameEnumerationResult previousResult, bool recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumerateSubNamesAsync (name As Uri, previousResult As NameEnumerationResult, recursive As Boolean) As Task(Of NameEnumerationResult)" />
      <MemberSignature Language="F#" Value="member this.EnumerateSubNamesAsync : Uri * System.Fabric.NameEnumerationResult * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;" Usage="propertyManagementClient.EnumerateSubNamesAsync (name, previousResult, recursive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.NameEnumerationResult" />
        <Parameter Name="recursive" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>列挙する親サービス ファブリック名。</para>
        </param>
        <param name="previousResult">
          <para>列挙の前の呼び出しによって返された結果。 最初の呼び出しでは、これは null です。</para>
        </param>
        <param name="recursive">
          <para>
            <languageKeyword>True</languageKeyword>列挙体は再帰的なをする必要があります。</para>
        </param>
        <summary>
          <para>指定した名前の下のすべての Service Fabric 名を列挙します。 </para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を列挙します。</para>
          <para>以下を参照してください。<see cref="T:System.Fabric.NameEnumerationResult" /></para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumerateSubNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync (Uri name, System.Fabric.NameEnumerationResult previousResult, bool recursive, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync(class System.Uri name, class System.Fabric.NameEnumerationResult previousResult, bool recursive, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnumerateSubNamesAsync : Uri * System.Fabric.NameEnumerationResult * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;" Usage="propertyManagementClient.EnumerateSubNamesAsync (name, previousResult, recursive, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.NameEnumerationResult" />
        <Parameter Name="recursive" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>列挙する親サービス ファブリック名。</para>
        </param>
        <param name="previousResult">
          <para>列挙の前の呼び出しによって返された結果。 最初の呼び出しでは、これは null です。</para>
        </param>
        <param name="recursive">
          <para>
            <languageKeyword>True</languageKeyword>場合は、列挙体は再帰的なをする必要があります。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定した名前の下のすべての Service Fabric 名を列挙します。</para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を列挙します。</para>
          <para>以下を参照してください。<see cref="T:System.Fabric.NameEnumerationResult" /></para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="name" />存在しません。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt; GetPropertyAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedProperty&gt; GetPropertyAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyAsync (parentName As Uri, propertyName As String) As Task(Of NamedProperty)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;" Usage="propertyManagementClient.GetPropertyAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>プロパティの親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <summary>
          <para>指定した <see cref="T:System.Fabric.NamedProperty" /> を取得します。</para>
        </summary>
        <returns>
          <para>非同期の get 操作を表すタスク。</para>
          <para>以下を参照してください。<see cref="T:System.Fabric.NamedProperty" /></para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt; GetPropertyAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedProperty&gt; GetPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;" Usage="propertyManagementClient.GetPropertyAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>プロパティの親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定した <see cref="T:System.Fabric.NamedProperty" /> を取得します。 </para>
        </summary>
        <returns>
          <para>非同期の get 操作を表すタスク。</para>
          <para>以下を参照してください。<see cref="T:System.Fabric.NamedProperty" /></para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyMetadataAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyMetadataAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyMetadataAsync (parentName As Uri, propertyName As String) As Task(Of NamedPropertyMetadata)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyMetadataAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;" Usage="propertyManagementClient.GetPropertyMetadataAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>プロパティの親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>プロパティの名前です。</para>
        </param>
        <summary>
          <para>指定した <see cref="T:System.Fabric.NamedPropertyMetadata" /> を取得します。</para>
        </summary>
        <returns>
          <para>非同期の get 操作を表すタスク。</para>
          <para>以下を参照してください。<see cref="T:System.Fabric.NamedPropertyMetadata" /></para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyMetadataAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyMetadataAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyMetadataAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;" Usage="propertyManagementClient.GetPropertyMetadataAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>プロパティの親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>プロパティの名前です。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。
            操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定した <see cref="T:System.Fabric.NamedPropertyMetadata" /> を取得します。</para>
        </summary>
        <returns>
          <para>非同期の get 操作を表すタスク。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />指定したプロパティが存在しない場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>    
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NameExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NameExistsAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NameExistsAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.NameExistsAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function NameExistsAsync (name As Uri) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameExistsAsync : Uri -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="propertyManagementClient.NameExistsAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Service Fabric 名前です。</para>
        </param>
        <summary>
          <para>返します<languageKeyword>true</languageKeyword> Service Fabric の指定した名前が存在する場合。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>
            <languageKeyword>true</languageKeyword> Service Fabric の指定した名前が存在する場合それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
          <para>
            <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />クラスターを検証する方法の 1 つはおよび<see cref="T:System.Fabric.FabricClient" />クラスターに接続できます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NameExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NameExistsAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NameExistsAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.NameExistsAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.NameExistsAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="propertyManagementClient.NameExistsAsync (name, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Service Fabric 名前です。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>返します<languageKeyword>true</languageKeyword> Service Fabric の指定した名前が存在する場合。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
          <para>
            <languageKeyword>true</languageKeyword> Service Fabric の指定した名前が存在する場合それ以外の場合、 <languageKeyword>false</languageKeyword>です。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutCustomPropertyOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutCustomPropertyOperationAsync (Uri name, System.Fabric.PutCustomPropertyOperation operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutCustomPropertyOperationAsync(class System.Uri name, class System.Fabric.PutCustomPropertyOperation operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutCustomPropertyOperationAsync(System.Uri,System.Fabric.PutCustomPropertyOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutCustomPropertyOperationAsync (name As Uri, operation As PutCustomPropertyOperation) As Task" />
      <MemberSignature Language="F#" Value="member this.PutCustomPropertyOperationAsync : Uri * System.Fabric.PutCustomPropertyOperation -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutCustomPropertyOperationAsync (name, operation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="operation" Type="System.Fabric.PutCustomPropertyOperation" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="operation">
          <para>Put 操作パラメーターは、プロパティ名、値、およびカスタム型の情報を含むです。</para>
        </param>
        <summary>
          <para>作成または更新によって記述された指定の Service Fabric プロパティ<see cref="T:System.Fabric.PutCustomPropertyOperation" />下にある指定された名前です。</para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="name" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutCustomPropertyOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutCustomPropertyOperationAsync (Uri name, System.Fabric.PutCustomPropertyOperation operation, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutCustomPropertyOperationAsync(class System.Uri name, class System.Fabric.PutCustomPropertyOperation operation, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutCustomPropertyOperationAsync(System.Uri,System.Fabric.PutCustomPropertyOperation,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutCustomPropertyOperationAsync : Uri * System.Fabric.PutCustomPropertyOperation * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutCustomPropertyOperationAsync (name, operation, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="operation" Type="System.Fabric.PutCustomPropertyOperation" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="operation">
          <para>Put 操作パラメーターは、プロパティ名、値、およびカスタム型の情報を含むです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。
            操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>作成または更新によって記述された指定の Service Fabric プロパティ<see cref="T:System.Fabric.PutCustomPropertyOperation" />下にある指定された名前です。</para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="name" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="name" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Byte()) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * byte[] -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <summary>
          <para>作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Byte" />は指定された名前の配列。 </para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, double value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, float64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Double) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * double -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <summary>
          <para>作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Double" />下にある指定された名前です。
            </para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, Guid value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.Guid value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Guid) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * Guid -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <summary>
          <para>作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Guid" />下にある指定された名前です。 </para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * int64 -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <summary>
          <para>作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Int64" />下にある指定された名前です。 </para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As String) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * string -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <summary>
          <para>作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.String" />下にある指定された名前です。 </para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, byte[] value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, unsigned int8[] value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Byte[],System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * byte[] * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。
            操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Byte" />は指定された名前の配列。</para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, double value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, float64 value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Double,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * double * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Double" />下にある指定された名前です。</para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, Guid value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.Guid value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。
            操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Guid" />下にある指定された名前です。</para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, long value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, int64 value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.Int64" />下にある指定された名前です。</para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, string value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, string value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>親サービス ファブリック名。</para>
        </param>
        <param name="propertyName">
          <para>Service Fabric プロパティの名前。</para>
        </param>
        <param name="value">
          <para>プロパティの値。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認します。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>作成または更新の種類の指定した Service Fabric プロパティ<see cref="T:System.String" />下にある指定された名前です。</para>
        </summary>
        <returns>
          <para>表す非同期のタスクは、操作を配置します。</para>
        </returns>
        <remarks>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />ときに返される<paramref name="value" />1 MB を超えています。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SubmitPropertyBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync (Uri parentName, System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; operations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync(class System.Uri parentName, class System.Collections.Generic.ICollection`1&lt;class System.Fabric.PropertyBatchOperation&gt; operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation})" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitPropertyBatchAsync (parentName As Uri, operations As ICollection(Of PropertyBatchOperation)) As Task(Of PropertyBatchResult)" />
      <MemberSignature Language="F#" Value="member this.SubmitPropertyBatchAsync : Uri * System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;" Usage="propertyManagementClient.SubmitPropertyBatchAsync (parentName, operations)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="operations" Type="System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt;" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>プロパティ バッチ操作を実行する親サービス ファブリック名。</para>
        </param>
        <param name="operations">
          <para>バッチ プロパティ操作です。</para>
        </param>
        <summary>
          <para>バッチ送信<see cref="T:System.Fabric.PropertyBatchOperation" />です。</para>
        </summary>
        <returns>
          <para>非同期の get 操作を表すタスク。</para>
          <para>以下を参照してください。<see cref="T:System.Fabric.PropertyBatchResult" /></para>
        </returns>
        <remarks>
          <para>いずれかまたはすべてのバッチ内の操作がコミットされます。 </para>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />プロパティ値が 1 MB より大きい場合に返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" />少なくとも 1 つチェック操作のユーザーに提供されている場合に返される<paramref name="operations" />に失敗しました。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SubmitPropertyBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync (Uri parentName, System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; operations, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync(class System.Uri parentName, class System.Collections.Generic.ICollection`1&lt;class System.Fabric.PropertyBatchOperation&gt; operations, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SubmitPropertyBatchAsync : Uri * System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;" Usage="propertyManagementClient.SubmitPropertyBatchAsync (parentName, operations, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="operations" Type="System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para>プロパティ バッチ操作を実行する親サービス ファブリック名。</para>
        </param>
        <param name="operations">
          <para>バッチ プロパティ操作です。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>バッチ送信<see cref="T:System.Fabric.PropertyBatchOperation" />s。 いずれかまたはすべてのバッチ内の操作がコミットされます。</para>
        </summary>
        <returns>
          <para>非同期の get 操作を表すタスク。</para>
          <para>以下を参照してください。<see cref="T:System.Fabric.PropertyBatchResult" /></para>
        </returns>
        <remarks>
          <para>いずれかまたはすべてのバッチ内の操作がコミットされます。 </para>
          <para>操作のタイムアウトは、既定のタイムアウト値 (1 分) に設定されます。</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>次のいずれかによって発生します。</para>
          <para>1 つまたは複数の引数が無効である E_INVALIDARG が返されます。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para>次のいずれかによって発生します。</para>
          <para>Null 参照が渡されるときに、E_POINTER が返される有効な引数として受け付けないメソッドにします。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />ユーザーが指定したときに返される<paramref name="parentName" />存在しません。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />この書き込み操作が別の書き込み操作で競合する場合に返されます。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>次のいずれかによって発生します。</para>
          <para>操作が中止されました E_ABORT が返されます。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>次のいずれかによって発生します。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />ときに返される<paramref name="parentName" />有効なサービス ファブリック名ではありません。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />プロパティ値が 1 MB より大きい場合に返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" />少なくとも 1 つチェック操作のユーザーに提供されている場合に返される<paramref name="operations" />に失敗しました。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para>内部エラーが発生した場合は、この例外がスローされます。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>