<Type Name="SchemaInfoErrorCode" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode">
  <TypeSignature Language="C#" Value="public enum SchemaInfoErrorCode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SchemaInfoErrorCode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode" />
  <TypeSignature Language="VB.NET" Value="Public Enum SchemaInfoErrorCode" />
  <TypeSignature Language="F#" Value="type SchemaInfoErrorCode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="6122e-101">SchemaInfoCollection で発生したエラーの考えられる。</span><span class="sxs-lookup"><span data-stu-id="6122e-101">Possible errors encountered by SchemaInfoCollection.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="SchemaInfoNameConflict">
      <MemberSignature Language="C#" Value="SchemaInfoNameConflict" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode SchemaInfoNameConflict = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode.SchemaInfoNameConflict" />
      <MemberSignature Language="VB.NET" Value="SchemaInfoNameConflict" />
      <MemberSignature Language="F#" Value="SchemaInfoNameConflict = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode.SchemaInfoNameConflict" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6122e-102">A<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />指定した名前のエントリが既に存在します。</span><span class="sxs-lookup"><span data-stu-id="6122e-102">A <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> entry with the given name already exists.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="SchemaInfoNameDoesNotExist">
      <MemberSignature Language="C#" Value="SchemaInfoNameDoesNotExist" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode SchemaInfoNameDoesNotExist = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode.SchemaInfoNameDoesNotExist" />
      <MemberSignature Language="VB.NET" Value="SchemaInfoNameDoesNotExist" />
      <MemberSignature Language="F#" Value="SchemaInfoNameDoesNotExist = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode.SchemaInfoNameDoesNotExist" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6122e-103">いいえ<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />指定した名前が存在します。</span><span class="sxs-lookup"><span data-stu-id="6122e-103">No <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> exists with the given name.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TableInfoAlreadyPresent">
      <MemberSignature Language="C#" Value="TableInfoAlreadyPresent" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode TableInfoAlreadyPresent = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode.TableInfoAlreadyPresent" />
      <MemberSignature Language="VB.NET" Value="TableInfoAlreadyPresent" />
      <MemberSignature Language="F#" Value="TableInfoAlreadyPresent = 2" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode.TableInfoAlreadyPresent" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfoErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6122e-104">指定されたテーブルのエントリは既に、<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />オブジェクト。</span><span class="sxs-lookup"><span data-stu-id="6122e-104">An entry for the given table already exists in the <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" /> object.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>