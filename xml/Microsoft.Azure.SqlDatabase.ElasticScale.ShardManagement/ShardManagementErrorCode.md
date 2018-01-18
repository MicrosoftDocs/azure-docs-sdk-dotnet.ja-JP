<Type Name="ShardManagementErrorCode" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode">
  <TypeSignature Language="C#" Value="public enum ShardManagementErrorCode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ShardManagementErrorCode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ShardManagementErrorCode" />
  <TypeSignature Language="F#" Value="type ShardManagementErrorCode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="f3090-101">関連するエラー コードを表す<see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" />操作します。</span><span class="sxs-lookup"><span data-stu-id="f3090-101">Represents error codes related to <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardMapManager" /> operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GlobalStoreOperationInsufficientParameters">
      <MemberSignature Language="C#" Value="GlobalStoreOperationInsufficientParameters" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode GlobalStoreOperationInsufficientParameters = int32(8)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.GlobalStoreOperationInsufficientParameters" />
      <MemberSignature Language="VB.NET" Value="GlobalStoreOperationInsufficientParameters" />
      <MemberSignature Language="F#" Value="GlobalStoreOperationInsufficientParameters = 8" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.GlobalStoreOperationInsufficientParameters" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-102">GSM ストアド プロシージャのすべての必要なパラメーターが指定されていません。</span><span class="sxs-lookup"><span data-stu-id="f3090-102">All necessary parameters for GSM stored procedure are not supplied.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="GlobalStoreVersionMismatch">
      <MemberSignature Language="C#" Value="GlobalStoreVersionMismatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode GlobalStoreVersionMismatch = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.GlobalStoreVersionMismatch" />
      <MemberSignature Language="VB.NET" Value="GlobalStoreVersionMismatch" />
      <MemberSignature Language="F#" Value="GlobalStoreVersionMismatch = 6" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.GlobalStoreVersionMismatch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-103">GSM ストアのバージョンは、クライアント ライブラリとは一致しません。</span><span class="sxs-lookup"><span data-stu-id="f3090-103">GSM store version does not match with client library.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LocalStoreOperationInsufficientParameters">
      <MemberSignature Language="C#" Value="LocalStoreOperationInsufficientParameters" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode LocalStoreOperationInsufficientParameters = int32(9)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.LocalStoreOperationInsufficientParameters" />
      <MemberSignature Language="VB.NET" Value="LocalStoreOperationInsufficientParameters" />
      <MemberSignature Language="F#" Value="LocalStoreOperationInsufficientParameters = 9" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.LocalStoreOperationInsufficientParameters" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>9</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-104">LSM ストアド プロシージャのすべての必要なパラメーターが指定されていません。</span><span class="sxs-lookup"><span data-stu-id="f3090-104">All necessary parameters for LSM stored procedure are not supplied.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LocalStoreVersionMismatch">
      <MemberSignature Language="C#" Value="LocalStoreVersionMismatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode LocalStoreVersionMismatch = int32(7)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.LocalStoreVersionMismatch" />
      <MemberSignature Language="VB.NET" Value="LocalStoreVersionMismatch" />
      <MemberSignature Language="F#" Value="LocalStoreVersionMismatch = 7" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.LocalStoreVersionMismatch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-105">クライアント ライブラリと LSM ストアのバージョンが一致しません。</span><span class="sxs-lookup"><span data-stu-id="f3090-105">LSM store version does not match with client library.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LockNotAcquired">
      <MemberSignature Language="C#" Value="LockNotAcquired" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode LockNotAcquired = int32(20)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.LockNotAcquired" />
      <MemberSignature Language="VB.NET" Value="LockNotAcquired" />
      <MemberSignature Language="F#" Value="LockNotAcquired = 20" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.LockNotAcquired" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>20</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-106">アプリケーション ロックを取得できませんでした。</span><span class="sxs-lookup"><span data-stu-id="f3090-106">An application lock could not be acquired.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LockNotReleased">
      <MemberSignature Language="C#" Value="LockNotReleased" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode LockNotReleased = int32(21)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.LockNotReleased" />
      <MemberSignature Language="VB.NET" Value="LockNotReleased" />
      <MemberSignature Language="F#" Value="LockNotReleased = 21" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.LockNotReleased" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>21</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-107">アプリケーション ロックでしたを解除できません。</span><span class="sxs-lookup"><span data-stu-id="f3090-107">An application lock cound not be released.</span></span> 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingDoesNotExist">
      <MemberSignature Language="C#" Value="MappingDoesNotExist" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode MappingDoesNotExist = int32(23)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingDoesNotExist" />
      <MemberSignature Language="VB.NET" Value="MappingDoesNotExist" />
      <MemberSignature Language="F#" Value="MappingDoesNotExist = 23" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingDoesNotExist" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>23</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-108">指定されたマッピングは不要になったに存在しています。</span><span class="sxs-lookup"><span data-stu-id="f3090-108">Specified mapping no longer exists.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingIsAlreadyLocked">
      <MemberSignature Language="C#" Value="MappingIsAlreadyLocked" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode MappingIsAlreadyLocked = int32(29)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingIsAlreadyLocked" />
      <MemberSignature Language="VB.NET" Value="MappingIsAlreadyLocked" />
      <MemberSignature Language="F#" Value="MappingIsAlreadyLocked = 29" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingIsAlreadyLocked" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>29</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-109">指定されたマッピングは既にロックされています</span><span class="sxs-lookup"><span data-stu-id="f3090-109">Specified mapping has already been locked</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingIsNotOffline">
      <MemberSignature Language="C#" Value="MappingIsNotOffline" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode MappingIsNotOffline = int32(27)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingIsNotOffline" />
      <MemberSignature Language="VB.NET" Value="MappingIsNotOffline" />
      <MemberSignature Language="F#" Value="MappingIsNotOffline = 27" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingIsNotOffline" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>27</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-110">指定されたマッピングがオフラインの管理の特定の操作を保証します。</span><span class="sxs-lookup"><span data-stu-id="f3090-110">Specified mapping is not offline which certain management operations warrant.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingIsOffline">
      <MemberSignature Language="C#" Value="MappingIsOffline" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode MappingIsOffline = int32(25)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingIsOffline" />
      <MemberSignature Language="VB.NET" Value="MappingIsOffline" />
      <MemberSignature Language="F#" Value="MappingIsOffline = 25" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingIsOffline" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>25</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-111">指定されたマッピングはオフラインです。</span><span class="sxs-lookup"><span data-stu-id="f3090-111">Specified mapping is offline.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingLockOwnerIdDoesNotMatch">
      <MemberSignature Language="C#" Value="MappingLockOwnerIdDoesNotMatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode MappingLockOwnerIdDoesNotMatch = int32(28)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingLockOwnerIdDoesNotMatch" />
      <MemberSignature Language="VB.NET" Value="MappingLockOwnerIdDoesNotMatch" />
      <MemberSignature Language="F#" Value="MappingLockOwnerIdDoesNotMatch = 28" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingLockOwnerIdDoesNotMatch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>28</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-112">指定されたマッピングがロックされているし、指定されたロック所有者の id が、ストアの所有者の id と一致しません</span><span class="sxs-lookup"><span data-stu-id="f3090-112">Specified mapping is locked and the given lock owner id does not match the owner id in the store</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingNotFoundForKey">
      <MemberSignature Language="C#" Value="MappingNotFoundForKey" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode MappingNotFoundForKey = int32(24)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingNotFoundForKey" />
      <MemberSignature Language="VB.NET" Value="MappingNotFoundForKey" />
      <MemberSignature Language="F#" Value="MappingNotFoundForKey = 24" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingNotFoundForKey" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>24</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-113">マッピングに対応する、指定したキーを特定できませんでした。</span><span class="sxs-lookup"><span data-stu-id="f3090-113">Could not locate a mapping corresponding to given key.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingPointAlreadyMapped">
      <MemberSignature Language="C#" Value="MappingPointAlreadyMapped" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode MappingPointAlreadyMapped = int32(15)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingPointAlreadyMapped" />
      <MemberSignature Language="VB.NET" Value="MappingPointAlreadyMapped" />
      <MemberSignature Language="F#" Value="MappingPointAlreadyMapped = 15" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingPointAlreadyMapped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>15</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-114">特定のポイントが既に関連付けマッピングです。</span><span class="sxs-lookup"><span data-stu-id="f3090-114">Given point is already associated with a mapping.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingRangeAlreadyMapped">
      <MemberSignature Language="C#" Value="MappingRangeAlreadyMapped" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode MappingRangeAlreadyMapped = int32(16)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingRangeAlreadyMapped" />
      <MemberSignature Language="VB.NET" Value="MappingRangeAlreadyMapped" />
      <MemberSignature Language="F#" Value="MappingRangeAlreadyMapped = 16" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingRangeAlreadyMapped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-115">指定された範囲によって既に使用されてマッピングします。</span><span class="sxs-lookup"><span data-stu-id="f3090-115">Specified range is already associated with a mapping.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="MappingsKillConnectionFailure">
      <MemberSignature Language="C#" Value="MappingsKillConnectionFailure" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode MappingsKillConnectionFailure = int32(26)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingsKillConnectionFailure" />
      <MemberSignature Language="VB.NET" Value="MappingsKillConnectionFailure" />
      <MemberSignature Language="F#" Value="MappingsKillConnectionFailure = 26" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.MappingsKillConnectionFailure" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>26</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-116">指定されたマッピングに関連付けられている接続を終了できませんでした。</span><span class="sxs-lookup"><span data-stu-id="f3090-116">Could not terminate connections associated with the Specified mapping.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardAlreadyExists">
      <MemberSignature Language="C#" Value="ShardAlreadyExists" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardAlreadyExists = int32(12)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardAlreadyExists" />
      <MemberSignature Language="VB.NET" Value="ShardAlreadyExists" />
      <MemberSignature Language="F#" Value="ShardAlreadyExists = 12" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardAlreadyExists" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>12</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-117">シャードは既に存在します。</span><span class="sxs-lookup"><span data-stu-id="f3090-117">Shard already exists.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardDoesNotExist">
      <MemberSignature Language="C#" Value="ShardDoesNotExist" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardDoesNotExist = int32(19)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardDoesNotExist" />
      <MemberSignature Language="VB.NET" Value="ShardDoesNotExist" />
      <MemberSignature Language="F#" Value="ShardDoesNotExist = 19" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardDoesNotExist" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>19</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-118">シャードはこれ以上存在しません。</span><span class="sxs-lookup"><span data-stu-id="f3090-118">Shard does not exist any more.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardHasMappings">
      <MemberSignature Language="C#" Value="ShardHasMappings" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardHasMappings = int32(11)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardHasMappings" />
      <MemberSignature Language="VB.NET" Value="ShardHasMappings" />
      <MemberSignature Language="F#" Value="ShardHasMappings = 11" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardHasMappings" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>11</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-119">シャードには、関連付けられているマッピングがあります。</span><span class="sxs-lookup"><span data-stu-id="f3090-119">Shard has mappings associated with it.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardLocationAlreadyExists">
      <MemberSignature Language="C#" Value="ShardLocationAlreadyExists" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardLocationAlreadyExists = int32(13)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardLocationAlreadyExists" />
      <MemberSignature Language="VB.NET" Value="ShardLocationAlreadyExists" />
      <MemberSignature Language="F#" Value="ShardLocationAlreadyExists = 13" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardLocationAlreadyExists" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>13</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-120">シャードの場所は既に存在します。</span><span class="sxs-lookup"><span data-stu-id="f3090-120">Shard location already exists.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardMapAlreadyExists">
      <MemberSignature Language="C#" Value="ShardMapAlreadyExists" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardMapAlreadyExists = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapAlreadyExists" />
      <MemberSignature Language="VB.NET" Value="ShardMapAlreadyExists" />
      <MemberSignature Language="F#" Value="ShardMapAlreadyExists = 3" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapAlreadyExists" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-121">指定した名前を持つ Shardmap は既に存在します。</span><span class="sxs-lookup"><span data-stu-id="f3090-121">Shardmap with specified name already exists.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardMapDoesNotExist">
      <MemberSignature Language="C#" Value="ShardMapDoesNotExist" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardMapDoesNotExist = int32(18)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapDoesNotExist" />
      <MemberSignature Language="VB.NET" Value="ShardMapDoesNotExist" />
      <MemberSignature Language="F#" Value="ShardMapDoesNotExist = 18" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapDoesNotExist" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>18</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-122">Shardmap はこれ以上存在しません。</span><span class="sxs-lookup"><span data-stu-id="f3090-122">Shardmap does not exist any more.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardMapHasShards">
      <MemberSignature Language="C#" Value="ShardMapHasShards" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardMapHasShards = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapHasShards" />
      <MemberSignature Language="VB.NET" Value="ShardMapHasShards" />
      <MemberSignature Language="F#" Value="ShardMapHasShards = 5" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapHasShards" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-123">Shardmap には、関連付けられているシャードがあります。</span><span class="sxs-lookup"><span data-stu-id="f3090-123">Shardmap has shards associated with it.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardMapLookupFailure">
      <MemberSignature Language="C#" Value="ShardMapLookupFailure" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardMapLookupFailure = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapLookupFailure" />
      <MemberSignature Language="VB.NET" Value="ShardMapLookupFailure" />
      <MemberSignature Language="F#" Value="ShardMapLookupFailure = 4" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapLookupFailure" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-124">指定した名前が見つかりません。 Shardmap です。</span><span class="sxs-lookup"><span data-stu-id="f3090-124">Shardmap with specified name not found.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardMapManagerStoreAlreadyExists">
      <MemberSignature Language="C#" Value="ShardMapManagerStoreAlreadyExists" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardMapManagerStoreAlreadyExists = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapManagerStoreAlreadyExists" />
      <MemberSignature Language="VB.NET" Value="ShardMapManagerStoreAlreadyExists" />
      <MemberSignature Language="F#" Value="ShardMapManagerStoreAlreadyExists = 1" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapManagerStoreAlreadyExists" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-125">ストアは、対象シャードのマップ manager データベースに既に存在します。</span><span class="sxs-lookup"><span data-stu-id="f3090-125">Store already exists on target shard map manager database.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardMapManagerStoreDoesNotExist">
      <MemberSignature Language="C#" Value="ShardMapManagerStoreDoesNotExist" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardMapManagerStoreDoesNotExist = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapManagerStoreDoesNotExist" />
      <MemberSignature Language="VB.NET" Value="ShardMapManagerStoreDoesNotExist" />
      <MemberSignature Language="F#" Value="ShardMapManagerStoreDoesNotExist = 2" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapManagerStoreDoesNotExist" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-126">ストアは、対象シャードのマップ manager データベースに存在しません。</span><span class="sxs-lookup"><span data-stu-id="f3090-126">Store does not exist on target shard map manager database.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardMapTypeConversionError">
      <MemberSignature Language="C#" Value="ShardMapTypeConversionError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardMapTypeConversionError = int32(10)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapTypeConversionError" />
      <MemberSignature Language="VB.NET" Value="ShardMapTypeConversionError" />
      <MemberSignature Language="F#" Value="ShardMapTypeConversionError = 10" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardMapTypeConversionError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>10</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-127">シャード マップの変換に失敗しました。</span><span class="sxs-lookup"><span data-stu-id="f3090-127">Conversion of shard map failed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardNotValid">
      <MemberSignature Language="C#" Value="ShardNotValid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardNotValid = int32(30)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardNotValid" />
      <MemberSignature Language="VB.NET" Value="ShardNotValid" />
      <MemberSignature Language="F#" Value="ShardNotValid = 30" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardNotValid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>30</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-128">シャードのストレージ構造体ではありません。</span><span class="sxs-lookup"><span data-stu-id="f3090-128">Shard does not have storage structures.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ShardVersionMismatch">
      <MemberSignature Language="C#" Value="ShardVersionMismatch" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode ShardVersionMismatch = int32(14)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardVersionMismatch" />
      <MemberSignature Language="VB.NET" Value="ShardVersionMismatch" />
      <MemberSignature Language="F#" Value="ShardVersionMismatch = 14" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.ShardVersionMismatch" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>14</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-129">シャードは同時実行ユーザーによって更新されました。</span><span class="sxs-lookup"><span data-stu-id="f3090-129">Shard has been updated by concurrent user.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="StorageOperationFailure">
      <MemberSignature Language="C#" Value="StorageOperationFailure" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode StorageOperationFailure = int32(17)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.StorageOperationFailure" />
      <MemberSignature Language="VB.NET" Value="StorageOperationFailure" />
      <MemberSignature Language="F#" Value="StorageOperationFailure = 17" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.StorageOperationFailure" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>17</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-130">記憶域操作が失敗しました。</span><span class="sxs-lookup"><span data-stu-id="f3090-130">Storage operation failed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="Success" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode Success = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.Success" />
      <MemberSignature Language="VB.NET" Value="Success" />
      <MemberSignature Language="F#" Value="Success = 0" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.Success" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-131">正常に実行します。</span><span class="sxs-lookup"><span data-stu-id="f3090-131">Successful execution.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="UnexpectedError">
      <MemberSignature Language="C#" Value="UnexpectedError" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode UnexpectedError = int32(22)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.UnexpectedError" />
      <MemberSignature Language="VB.NET" Value="UnexpectedError" />
      <MemberSignature Language="F#" Value="UnexpectedError = 22" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode.UnexpectedError" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.ShardManagementErrorCode</ReturnType>
      </ReturnValue>
      <MemberValue>22</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3090-132">予期しないエラーが発生しました。</span><span class="sxs-lookup"><span data-stu-id="f3090-132">An unexpected error has occurred.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>