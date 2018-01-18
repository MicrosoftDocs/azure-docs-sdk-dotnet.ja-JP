<Type Name="ConnectionOptions" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions">
  <TypeSignature Language="C#" Value="public enum ConnectionOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectionOptions extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectionOptions" />
  <TypeSignature Language="F#" Value="type ConnectionOptions = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f0928-101">シャードのマップ マネージャーによって開かれた接続で実行する、検証などの操作を指定することができます。</span><span class="sxs-lookup"><span data-stu-id="f0928-101">Allows users to specify operations such as validation, to perform on the connection opened by the shard map manager.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="None">
      <MemberSignature Language="C#" Value="None" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions None = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.None" />
      <MemberSignature Language="VB.NET" Value="None" />
      <MemberSignature Language="F#" Value="None = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.None" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0928-102">開いている接続では、演算は実行されません。</span><span class="sxs-lookup"><span data-stu-id="f0928-102">No operation will be performed on the opened connection.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="Validate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions Validate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />
      <MemberSignature Language="VB.NET" Value="Validate" />
      <MemberSignature Language="F#" Value="Validate = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions.Validate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ConnectionOptions</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0928-103">検証は、対応するマッピングの状態がクライアントで前回のマッピング情報のキャッシュ以降に変更していないことを確認してください。 への接続で実行されます。</span><span class="sxs-lookup"><span data-stu-id="f0928-103">Validation will be performed on the connection to ensure that the state of the corresponding mapping has not changed since the mapping information was last cached at the client.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>